

<b>MATHEMATICS FOR MACHINE LEARNING</b>
<br></br>
This repository contains code and theory of mathematical concepts required to master Machine Learning.
This repository will give any budding beginner in Machine Learning a solid foundation on the important concepts 
in <b>Linear Algebra</b> and <b>Multivariate Calculus</b>.I have included IPython notebooks which has code snippets and important
explanations.
<br></br>
<b>So, Go ahead, Fork this repo and Happy Machine Learning :)</b>
<br></br>
<b>TABLE OF CONTENTS: </b>
<br></br>
<b>1. LINEAR ALGEBRA: <b>
<br></br>

-Linear Algebra Intuition:
```python
#Definition of Linear Algebra:

#Ans: Linear Algebra can be defined as the study of vectors,vector spaces and mapping between vector spaces.
#     It emerged from the study of matrices and the knowledge that they can be solved using system of linear equations.

#Use cases of Linear Algebra:

#Ans: 1. Solving of linear equations like:
         2a+3b=10
         7b+5c=20
         The above eqaution can be decomposed into matrices and vectors like:
         [2 3 [a]=[10]
          7 5][b] [20]
#     2. Optimization Problem:
#        Another use can be to fit a line that best matches a data distribution.The objective is to find the 
#        line or curve that best fits the data distribution by finding the optimal parameters of the line.

# Exercise:

#Solve the system of equations given by:

3x−2y+z=7
x+y+z=2
3x−2y−z=3
```
<br></br>

-Vector Space in DataScience:
```python
#Vectors in Machine Learning:

Ans: From a Computer Science point of view,A vector can be defined as a list of numbers.
     From a Physical point of view, a vector can be defined as a position in 3D space.
     If we visualize the parameters or features of an entity, a vector can be visualized spatially as
     a point in the 3D space.The vector can move in the the N dimensional feature space to find the globally
     locally optimum set of features  in the feature space.
     So, it is very important to visulize the features as vectors in the N dimensional feature space, so Linear 
     Algebra routines, and calculus formulaes can be applied in oder to solve them.
```
<br></br>
-Vector_Operations:
```python
#Vector Operations:

# There are two fundamental operations that can be performed on vectors

# 1. Vector addition and Subtraction:
#    Lets us define a co-ordinate space X,Y with two unit vectors X and Y. The space spanned by the 
#    unit vectors is called the co-ordinate space.These unit vectors X and Y are called the basis vectors.

#    Vector addition and subtraction follows the associativity rule:
#    A+(B+C)=(A+B)+C

# 2. Multiplication by a scalar constant
#    If we multiply a vector with a scalar constant, each of the components of the scalar vector is multiplied
#    by the scalar constant.
#    c[A] = [cA]
#     [B]   [cB]
```
<br></br>
-Cosine_Dot_Product:
```python
#Modulus  and dot product of vectors
 # 1. The dot product or the projection product of two vectors can be explained as :
      r.s = |r||s|cos(theta) , where theta is the angle between the two vectors
      Dot product of two vectors satisfy the following properties:
      * r.s = s.r (Commutative)
      * r.(s+t) = r.s+r.t (Distributive)
      * r.(ks) = k(rs) (Associative over Scalar Multiplication)
 #2. If two vectors are orthogonal to each other , the the value of :
      * r.s = 0 , because the value of cos(90)=0
     If two vectors are parallel to each other, then the value of:
      * r.s = |r||s|, because the value of cos(0)=1
```
<br></br>
-Vector_Projection:
```python
# Projection:
  The dot product of two vectors is defined as :
  * a.b=|a||b|cos(theta)
  * The term |b|cos(theta) is defined as the projection of the vector b on to a
    Now, if we write :
    > (a.b)/|a|=|b|cos(theta), is called the scalar projection
    >  a(a.b)/|a||a|= vector projection
```
