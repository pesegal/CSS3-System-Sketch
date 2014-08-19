CSS3-System-Sketch
==================

CSS3 animated solar system in a sketch design using CSS3 animate capibilites. Inspired by a codeacademy tutorial. Works best in Chrome, tested in latest versions of Firefox and IE. 

## Design notes

To maintain label direction in sub-orbits requires utilizing harmonic sums to calculate correct inverse rotation speed.

```
For same direction: 
s = (1/x) + (1/y)

For opposite direction:
s = (1/x) - (1/y)

Where x and y are respective rotation speeds of the parent and child objects.
```


*Special thanks to Ed Piper for showing me harmonic sums.*
