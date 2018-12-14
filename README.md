# Python-Vectors

## Description
An implementation of P5.js' PVector in Python3.

## vector2D

### Paramters
#### x
The x component of the vector

#### y
The y component of the vector

### Methods

#### set(x_coord, y_coord)
Sets the x, y component of the vector.    

#### copy()
Return a copy of the vector. 

#### add(x_coord, y_coord)
Adds x and y components to the vector.

#### addVector2D(vector)
Adds one vector to the other.

#### sub(x_coord, y_coord)
Subtacts x and y components.

#### subVector2D(vector)
Subtacts one vector from the other.

#### mult(x_coord, y_coord)
Multiples the x and y components by the supplied coords.

#### multVector2D(vec)
Multiples two vectors together.

#### div(x_coord, y_coord)
Divides the x and y components by the supplied coords.

#### divVector2D(vector)
Divides two vectors x and y components.

#### mag()
Calculates the magnitude (length) of the vector.

#### magSq()
Calculates the squared magnitude (length) of the vector (Faster)

#### dot(x_coord, y_coord)
Calculates the dot product between the vector and an x and y coordinate.

#### dotVector2D(vec)
Calculates the dot product between two vectors.

#### dist(x_coord, y_coord)
Calculates the distance between the Vector and a point.

#### distVector2D(vec)
Calculates the distance between two Vectors.

#### normalise(mag_limit = 1)
Normalise the vector to a magnitude of mag_limit.

#### heading()
Calculates the heading of the Vector

#### rotate(angle)
Rotates the Vector by an angle given in radians.

#### angleBetween(x_coord, y_coord)
Calculates the angle in radians between the Vector and a point.

#### angleBetweenVector2D(vec)
Calculates the angle in radians between the Vector and a point.

#### lerp(x_coord, y_coord, amnt)
Linear interpolate the vector to a coord pair.

#### lerpVector2D( vec, amnt)
Linear interpolate the vector to another vector.

#### array()
Return an array 

#### intArray()
Returns an array of the rounded x, y values


## vector3D

### Paramters
#### x
The x component of the vector

#### y
The y component of the vector

#### z
The z component of the vector

### Methods

#### set(x_coord, y_coord, z_coord)
Sets the x, y and z component of the vector.    

#### copy()
Return a copy of the vector. 

#### add(x_coord, y_coord, z_coord)
Adds x, y and z components to the vector.

#### addVector3D(vector)
Adds one vector to the other.

#### sub(x_coord, y_coord, z_coord)
Subtacts x, y and z components.

#### subVector3D(vector)
Subtacts one vector from the other.

#### mult(x_coord, y_coord, z_coord)
Multiples the x, y and z components by the supplied coords.

#### multVector3D(vec)
Multiples two vectors together.

#### div(x_coord, y_coord, z_coord)
Divides the x, y and z components by the supplied coords.

#### divVector3D(vector)
Divides two vectors x, y and z components.

#### mag()
Calculates the magnitude (length) of the vector.

#### magSq()
Calculates the squared magnitude (length) of the vector (Faster)

#### dot(x_coord, y_coord, z_coord)
Calculates the dot product between the vector and an x, y and z coordinate.

#### dotVector3D(vec)
Calculates the dot product between two vectors.

#### dist(x_coord, y_coord, z_coord)
Calculates the distance between the Vector and a point.

#### distVector3D(vec)
Calculates the distance between two Vectors.

#### normalise(mag_limit = 1)
Normalise the vector to a magnitude of mag_limit.

#### angleBetween(x_coord, y_coord, z_coord)
Calculates the angle in radians between the Vector and a point.

#### angleBetweenVector3D(vec)
Calculates the angle in radians between the Vector and a point.

#### lerp(x_coord, y_coord, z_coord amnt)
Linear interpolate the vector to a coord triplet.

#### lerpVector3D( vec, amnt)
Linear interpolate the vector to another vector.

#### array()
Return an array 

#### intArray()
Returns an array of the rounded x, y and z values