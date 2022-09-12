# MATH

This folder will contain all the math required for my research

## Kepler's Laws of Planetary Motion
### First Law
A planet orbits the Sun in an ellipse, with the Sun at one of the focus of the ellipse.

### Second Law
A line connecting a planet to the Sun sweeps out equal area in equal time intervals.

### Third Law
Period cubed is proportional to semi-major axis squared.

#### Ellipses
For an ellipse, the sum of distance from the two focal points are a constant.
```text
r' + r = 2a
```

The relationship between the semi-major and semi-minor axis is:
```text
b^2 = a^2 (1 - e^2)
```

For an ellipse, the radius is given by:
```text
r = a(1-e^2)/(1 + e cos(theta)) (0 <= e < 1)
```

## Stellar Photometry
The magnitude of a star is a measure of its luminosity.

- Luminosity is the power output.

**Absolute Magnitude** refers to the magnitude viewed from a fixed distance (10 Parsecs away) (measure of intrinsic
luminosity)

- 1 Parsec is 3.26 light years

**Apparent Magnitude** is the magnitude viewed from Earth.

## Stellar Parallax

To measure the distance of a planet, we can use the approximation:
```text
d = 1/p
```
Where

- d is distance in parsec
- p is parallax angle in arc seconds 
  - This is using the approximation `sin(p) = p` which is reasonable as p is only a few seconds
- Method is only useful for stars close to Earth (less than 100pc)

## Distance Modulus
The distance can be determined using the following:
```text
m - M = 5 log(d/10)
```
Let 

- m = apparent magnitude
- M = absolute magnitude
- d = distance from star
- log is log base 10


## Blackbody Radiation
**Wien's Displacement Law**

```text
lambda_max = 2.898 micrometers/T
```


**Stefan-Boltzmann Law**
```text
L = 4 pi R^2 sigma T^4

L/L_sun = (M/M_Sun)^3.5

t/t_Sun = (M/M_Sun)^-2.5
```
