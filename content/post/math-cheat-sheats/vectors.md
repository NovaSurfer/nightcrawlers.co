---
title: "Vectors"
date: 2018-08-17T22:26:54+03:00
draft: false
tags:
  - math-cheat-sheets
---
# Vectors
A vector does not have a position; it has a magnitude and a direction. The components of
a vector measure signed displacement. In a two-dimensional vector for example, the first
component represents displacement on the X axis, while the second number represents
displacement on the Y axis.

#### 1.1 The W component
A vector can represent a point in space or a direction and a magnitude. A three-dimensional
vector has no context; there is no way to tell from the x, y, and z components if the vector is
supposed to be a point in space or a direction and a magnitude. In the context of games,
this is what the W component of a four-dimensional vector is used for.
If the W component is 0, the vector is a direction and a magnitude. If the W component is
anything else, usually 1, the vector is a point in space. This distinction seems arbitrary right
now; it has to do with matrix transformations, which will be covered in Chapter 3, Matrix
Transformations.

#### 1.2 Dot product
![](https://i.imgur.com/SMlmHD7.png)
The resulting scalar represents the directional relation of the vectors. That is, **A** * **B** represents how much **A** is pointing in the direction of **B**
Using the dot product we can tell if two vectors are pointing in the same direction or not following these rules:
+ If the dot product if **positive**, the vectors are pointing in the **same direction**
+ If the dot product if **negative**, the vectors point in **opposite directions**
+ If the dot product is **0**, the vectors are **perpendicular**


#### 1.2.1 Geometric definition
![](https://i.imgur.com/IIPdTY4.png)

#### 1.3 Magnitude
The magnitude or length of a vector is written as the letter of the vector surrounded by two bars, **||V||**. The magnitude of a vector is the square root of the dot product of the vector with itself.
![](https://i.imgur.com/UvlRWtq.png)



