# Trigonometry
## Table of contents
<!-- TOC -->

- [Trigonometry](#trigonometry)
    - [Table of contents](#table-of-contents)
    - [Triangle layout](#triangle-layout)
    - [Pythagorean theorem](#pythagorean-theorem)
        - [Introduction](#introduction)
        - [Solving sides of a right angled triangle](#solving-sides-of-a-right-angled-triangle)
            - [Case 1](#case-1)
            - [Case 2](#case-2)
            - [Case 3](#case-3)
    - [Trigonometric functions](#trigonometric-functions)
    - [Finding the angles of a right angled triangle](#finding-the-angles-of-a-right-angled-triangle)

<!-- /TOC -->

## Triangle layout
A right angled triangle has 3 sides: The adjacent, opposite and hypothenuse.

The hypothenuse (HYP in short) is the sloped angle of a right angled triangle. It is always opposite of the 90deg angle mark (marked `[]` in the diagram below).<br/>

The opposite (OPP in short) side is located opposite of a given angle (marked `Θ` in the diagram below).

The adjacent (ADJ in short) side is located adjacent to a given angle (marked `Θ` in the diagram below).
```
         Θ
         |\
         | \
ADJacent |  \  HYPothenuse
         |   \
         |    \
         []____\
         OPPosite
```
*Clarification for the naming of the triangle sides*

## Pythagorean theorem
### Introduction
The Pythagorean theorem can be used to find the sides of a right angled triangle. The theorem goes as follows:
```
a² + b² = c²
```
`a` and `b` are always the opposite and the adjacent sides of a right angled triangle, `c` is always the hypothenuse.

### Solving sides of a right angled triangle
#### Case 1
What is the value of C?

`c = sqrt(a² + b²)`<br/>
`c = 5`

```
         a = 4
       _______
      []     /
      |     /
      |    /
b = 3 |   /   c = ?
      |  /
      | /
      |/
```
*Triangle for case 1*

#### Case 2
What is the value of B?

`a² + b² = c²`<br/>
`4² + b² = 5²`<br/>

`4² = 16`<br/>
`5² = 25`<br/>
`c² - b² = (25 - 16) = 9`<br/>
`b² = 9`<br/>
`b = sqrt(9) = 3`<br/>

```
         a = 4
       _______
      []     /
      |     /
      |    /
b = ? |   /   c = 5
      |  /
      | /
      |/
```
*Triangle for case 2*

#### Case 3
What is the value of A?

`a² + b² = c²`<br/>
`a² + 3² = 5²`<br/>

`3² = 9`<br/>
`5² = 25`<br/>
`c² - a² = (25 - 9) = 16`<br/>
`b² = 16`<br/>
`b = sqrt(16) = 4`<br/>

```
         a = ?
       _______
      []     /
      |     /
      |    /
b = 3 |   /   c = 5
      |  /
      | /
      |/
```
*Triangle for case 3*

## Trigonometric functions
Θ (Theta) refers to the unknown measure of an angle. We use it to refer to an angle that needs to be found, or is unknown.

SOH = sin(Θ) = OPP/ADJ<br/>
CAH = cos(Θ) = ADJ/HYP<br/>
TOA = tan(Θ) = OPP/ADJ<br/>

## Finding the angles of a right angled triangle
The following explanation is going to use the basic triangle diagram below:
```
      3
  A ______ C
  []     /
  |     /
  |    /
4 |   /  5
  |  /
  | /
  |/
  B
```
*Basic triangle*

**Find the angle of B**<br/>
Find the angle of Θ:

To find the angle of Θ we first need to check which sides are closest to it. In this case sides ADJ and HYP are the closest. If we look at the trigonometric functions we can see that we need to use CAH (ADJ / HYP).

`Θ = (4 / 5) = 0.8 = 80deg`
```
         OPP
          3
      A ______ C
      []     /
      |     /
      |    /
ADJ 4 |   /  5 HYP
      |  /
      | /
      |/
      Θ
      B
```
*Diagram used for finding the angle of Θ*

**Find the angle of C**<br/>
Find the angle of Θ:

To find the angle of Θ we first need to check which sides are closest to it. In this case sides OPP and HYP are the closest. If we look at the trigonometric functions we can see that we need to use CAH (ADJ / HYP).

`Θ = (4 / 5) = 0.8 = 80deg`
```
         OPP
          3
      A ______ C
      []     /
      |     /
      |    /
ADJ 4 |   /  5 HYP
      |  /
      | /
      |/
      Θ
      B
```
*Diagram used for finding the angle of Θ*
