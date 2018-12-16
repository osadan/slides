<!-- .slide: data-background="./assets/2000px-WebGL_Logo.svg.png" -->

---

## description

---

>  JavaScript API for rendering interactive 2D and 3D graphics within any compatible web browser without the use of plug-ins

---

- using web standarts
- gpu accelerated usage
- using html element (canvas)
    - control code written in javascript :cupid"
    - shader code written in GLSL ES
    Note:  OpenGL ES Shading Language (GLSL ES), a language similar to C or C++, and is executed on a computer's graphics processing unit

---

## history

---

## Open GL

---

- 1990's Silicon Graphics created IRIS GL Api that become the standard and published it as open source called Open GL
- IRIS GL hardly relay on hardware  while Open GL made standart the hardware access api
- 1992 SGI created Open GL ARB(board) -
- 1995 microsoft release Direct3D

---

- 1997 Microsofy and SGI creaeted Fahrenheit trying to unify Direct3D and OpenGl interfaces
- 1998 HP joined the project
- 1999 Fahrenheit was abandoned ($$$)
- 2006 the board decided to give control to Khronos Group
- 2018 Apple deprecated Open GL api's and moved to Metal ApI

---

## WebGl

---

- 2006 - canvas prototype

- 2009 - khronos group started working groups involving Apple, Google, Mozilla, Opera

- 2011 specification was released
- 2012 Autodesc moved most of their application to local webgl clients (Fusion 360, AutoCad 360)
- 2013 started Webgl 2 specification
- 2017 finished the specification based on OpenGL es 3.0
- first implemntation on firefox 51 chrome 56 and opera 43

---

## The Graphic Pipeline

---

1. the program fills the memory buffers with arrays of vertics
2. this vertics is projected to screen space  (vertex shader) 
3. assembeld into triangles
4. resterized into pixel size fragments
5. assign color to the fragment (fragment shader)
6. getting drawn to the frame buffer

---

### vertex and elements array

----

 ### vertex array 
 set one or more vertex buffers , filled with arrays of vertex attributes (input to the vertex shader) 
 - location of the vertex in 3d space
 - 1..n texture information

----

 ### element array
order of the vertex
 
----
### vertex buffer
Both elements array and vertex array creates the vertex buffer (this all getting done in javascript)

---
## links
 [wikipedia](https://en.wikipedia.org/wiki/WebGL)
