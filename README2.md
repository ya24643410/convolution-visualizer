# Convolution Visualizer

This repository provides a visualized explanation of convolution for 



Convolution is a mathematical operation defined as where $x = a \pm n\Delta x \ ( n = 0, 1, 2, \cdots)$ represents a set of discrete points with the spacing

Convolution is a mathematical operation defined as

$$
(f \ast g) (t) = \int_{-\infty}^\infty f(\tau) g(t-\tau) d\tau
$$

This repository provides elementary learning materials for beginners in the finite-difference time-domain (FDTD) method. We will go through the basic topics of the FDTD method, including the basic update equations, etc. In each topic, we begin with theoretical concept interpretation and end with a practical coding example. After this course, you will have the ability to create your own simulation projects and we hope this course can become the startpoint of your amazing computational electromagnetics journey.

## Prerequisites

To fully understand these materials, it is better to have the following backgrounds:
1. Electromagnetism
2. Differential equations
3. Any programming language but we will use Julia in this course

## Usage

1. To access learning materials, just open certain julia notebook in the learning materials folder.
2. The codes are write under Julia version 1.12.4 with `Makie.jl`, so remember to set the environment before you run codes in Julia.
