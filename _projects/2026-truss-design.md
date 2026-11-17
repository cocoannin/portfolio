---
layout: project
title: Bridge Truss Design
description: Class project for MAE 2020: Statics and Mechanics of Solids
technologies:
  - MATLAB
  - Python
featured: false   # change to true to always show this project on your home page
image: /assets/images/function-graph.png
imagealt: Line plot titled "Analysis of Standard Functions" showing sin(x), cos(x) and 0.1*tan(x) for x from 0 to 10
---

> 📄 **Example page.** Replace all of it with your own project. The Latin text below is
> filler, here to show what a finished page looks like.

As part of a class project...Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut nec accumsan leo. Pellentesque ornare orci enim, vitae vestibulum nibh rutrum in. Donec pharetra risus nec ipsum fringilla, et mattis tortor auctor. Duis tortor ante, posuere ut odio a, scelerisque interdum purus. Pellentesque ornare orci enim, vitae vestibulum nibh rutrum in. Donec pharetra risus nec ipsum fringilla, et mattis tortor auctor. Duis tortor ante, posuere ut odio a, scelerisque interdum purus. Aenean faucibus luctus est, sed bibendum tellus. Nulla et magna urna. Morbi a ipsum sollicitudin, rhoncus risus volutpat, ultricies nunc. Quisque mollis finibus ante id imperdiet. Quisque vehicula elit sit amet felis facilisis fermentum.

1. Project background
The Ithaca community is planning to construct a lightweight pedestrian bridge across a
narrow gorge. The bridge must support pedestrians safely while minimizing the amount of
material used in its construction.
You have been hired to develop a suitable truss design.
You are responsible for:
1. Proposing a suitable truss configuration.
2. Selecting appropriate material, cross-sectional geometry and dimensions of each
member.
3. Verifying that the structure meets the required factor of safety.
4. Minimizing the total weight of the structure while satisfying all design requirements.
There is no single correct truss design. Your objective is to develop and justify an efficient
engineering solution.
2. Design requirements
Your proposed truss must satisfy the following specifications.
Parameter Design specification
Bridge span 12 m
Truss height 2.0–3.0 m
Bridge width 2.0 m
Maximum vertical load 30 kN
Minimum factor of safety 2.0
Maximum allowable vertical deflection 25 mm (**see below)
Support conditions Pin and roller
Structural configuration Planar, pin-jointed truss
Loading conditions

• The bridge must support a uniformly distributed pedestrian load equivalent to a 30
kN total vertical load.
• The loading must be transferred symmetrically to the two longitudinal trusses.
• Include the self-weight of the truss members in your final design verification.
In addition your design must be:
• Rigid.
• Constructed from straight members connected by idealized pin joints.
• Symmetrical about the centerline of the bridge.
** For the truss deflection analysis, you can use an approach we haven’t seen in class
called the unit-load method (or virtual work method). Search for “unit-load method for
truss deflection” to have a full description of the method.

We expect you to explain your design process on your portfolio page. This can include:
Executive summary and design objectives
Initial sketches and proposed truss geometry
Dimensioned engineering drawing
Free-body diagrams
Complete member-force analysis
Material and cross-section selection justification with stress analysis
Vertical deflection calculation
Total structural mass calculation
Comparison of design iterations
Final design drawing and engineering recommendations


This is how I solved the problem:

```python
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(0, 10, 500)
plt.plot(x, np.sin(x), label="sin(x)")
plt.plot(x, np.cos(x), label="cos(x)")
plt.legend()
```

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.
