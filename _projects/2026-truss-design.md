---
layout: project
title: Bridge Truss Design
description: 'Class project for MAE 2020: Statics and Mechanics of Solids'
technologies:
  - MATLAB
  - Python
featured: false   # change to true to always show this project on your home page
# image: /assets/images/function-graph.png
# imagealt: Line plot titled "Analysis of Standard Functions" showing sin(x), cos(x) and 0.1*tan(x) for x from 0 to 10 -->
---

As part of a class project, I was tasked with developing a suitable truss design for a lightweight pedestrian bridge across a narrow gorge. In proposing a suitable truss configuration, my goal was to select appropriate material, cross-sectional geometry and dimensions of each
member; verify that the structure meets the required factor of safety; and minimize the total weight of the structure while satisfying all design requirements.

### Design requirements:
- Bridge span: 12 m
- Truss height: 2.0–3.0 m
- Bridge width: 2.0 m
- Maximum vertical load: 30 kN
- Minimum factor of safety: 2.0
- Maximum allowable vertical deflection: 25 mm[^1]
- Support conditions: Pin and roller
- Structural configuration: Planar, pin-jointed truss
  
- Loading conditions:
  - The bridge must support a uniformly distributed pedestrian load equivalent to a 30 kN total vertical load.
  - The loading must be transferred symmetrically to the two longitudinal trusses.
  - Include the self-weight of the truss members in your final design verification.

- Construction requirements:
  - Rigid.
  - Constructed from straight members connected by idealized pin joints.
  - Symmetrical about the centerline of the bridge.
    
[^1]: For the truss deflection analysis, you can use an approach we haven’t seen in class called the unit-load method (or virtual work method).<\br>
Search for “unit-load method for truss deflection” to have a full description of the method.  

### Design process: 
- [ ] Executive summary and design objectives
- [ ] Initial sketches and proposed truss geometry
- [ ] Dimensioned engineering drawing
- [ ] Free-body diagrams
- [ ] Complete member-force analysis
- [ ] Material and cross-section selection justification with stress analysis
- [ ] Vertical deflection calculation
- [ ] Total structural mass calculation
- [ ] Comparison of design iterations
- [ ] Final design drawing and engineering recommendations

<br/>

> This is how I solved the problem:

<br/>

<!-- ```python
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(0, 10, 500)
plt.plot(x, np.sin(x), label="sin(x)")
plt.plot(x, np.cos(x), label="cos(x)")
plt.legend()
```

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.

[Formatting](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) -->
