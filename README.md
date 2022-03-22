# 104intersection

# Description:
This 1st year Epitech project is from the module math, and is the [4th project](https://github.com/Lukacms/104intersection/blob/main/assets/B-MAT-100_104intersection.pdf) <br>

It's about calculating if a ray of light goes through a scene object, here cylinders, spheres and cones.

## Language:
`Python3`

## Returns:
The program either returns `0` if everything is good, or `84` in case of errors. <br>
The errors can be:
* wrong number of arguments
* wrong type of argument given in parameter

# How to use the project
You can run the code like this:
```
./104intersection opt xp yp zp xv yv zv p
```
And the meaning of every parameter is:
```
opt surface option: 1 for a sphere, 2 for a cylinder, 3 for a cone

(xp, yp, zp) coordinates of a point by which the light ray passes through

(xv, yv, zv) coordinates of a vector parallel to the light ray

p parameter: radius of the sphere, radius of the cylinder, or angle formed by the cone and the Z-axis
```