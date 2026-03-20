# Convolution Visualizer

This repository provides a detailed explanation of convolution and a Julia-based visualization of the convolution of two rectangular functions, which makes the concept more concrete. It is designed to help beginners understand the concept of convolution and build an intuitive picture of this otherwise abstract concept.

## Convolution

Consider two functions $f(\tau)$ and $g(\tau)$, their convolution is defined as

$$
(f \ast g) (t) = \int_{-\infty}^\infty f(\tau) g(t-\tau) d\tau
$$

This operation looks complicated but can be divided into 5 steps.

### Step 1: Flip $g(\tau)$

Hence, 

$$
g(\tau) \rightarrow g(-\tau)
$$

### Step 2: Shift $g(\tau)$ by $t$

$$
g(-\tau) \rightarrow g(t-\tau)
$$

### Step 3: Times $f(\tau)$ and $g(t-\tau)$

$$
f(\tau) * g(t-\tau)
$$

### Step 4: Calculate the area under the new function

$$
\int_{-\infty}^\infty f(\tau) g(t-\tau) d\tau
$$

### Step 5: Repeat Step 1 to 4 with Another Value of $t$

$$
(f \ast g) (t)
$$

## Prerequisites

To fully understand these materials, it is better to have the following backgrounds:
1. Electromagnetism
2. Differential equations
3. Any programming language but we will use Julia in this course

## Usage

1. To access learning materials, just open certain julia notebook in the learning materials folder.
2. The codes are write under Julia version 1.12.4 with `Makie.jl`, so remember to set the environment before you run codes in Julia.
