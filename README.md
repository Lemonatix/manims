# Math Animations with 3b1b Manim

This repository contains a collection of math animations created using [Manim](https://github.com/3b1b/manim), the powerful math animation engine developed by [3Blue1Brown](https://www.3blue1brown.com/). 
The goal of these animations is to visualize mathematical concepts in a clear and engaging way—for personal learning and for explaining ideas to others.

---

## Table of Contents

1. [Overview](#overview)  
2. [Examples](#examples)  
3. [Getting Started](#getting-started)  
4. [Repository Structure](#repository-structure)  
5. [Running the Animations](#running-the-animations)  

---

## Overview

- **Purpose**: Create math animations to help visualize and understand various mathematical topics, from basic geometry to more advanced concepts.
- **Software**: [Manim](https://github.com/3b1b/manim) (3Blue1Brown’s custom python library for creating math animations).
- **Audience**: 
  - Personal learning and exploration of math concepts.
  - Teaching or sharing concepts with others (for now students and friends).

---

## Examples

Here are a few examples of what you will find soon in this repository:

- **Geometry**: Illustrations of triangle inequalities, circle theorems, or rotating shapes.  
- **Algebra & Calculus**: Scenes demonstrating functions, derivatives, integrals, series, etc.  
- **Linear Algebra**: Visualizing vectors, transformations, and matrix multiplication.  

Each animation has a corresponding `.py` file in the repository which you can render locally using Manim.

---

## Getting Started

### Prerequisites

1. **Python 3.7+**  
2. **Manim**  
   - Follow the [official Manim installation guide](https://docs.manim.community/en/stable/installation.html) or clone the [3b1b Manim repo](https://github.com/3b1b/manim) directly.
   
or just use:
```bash
pip install manim
```

3. **Dependencies**  
   - Install additional Python packages as required (e.g., `numpy`, `matplotlib`, etc.).  

### Installation

1. **Clone this repository**:
   ```bash
   git clone https://github.com/Lemonatix/manims.git
   cd manims

## Repository structure
manims/ \ 
├── example_scenes/ \
│   ├── geometry_scenes.py \
│   ├── algebra_scenes.py \
│   └── ... \
├── README.md \
└── ...


## Running the animations
1. Navigate to the folder containing the .py files if you aren't there yet:

```bash
cd example_scenes
```

2. To Run a scene use the Manim command:
```bash
manim geometry_scenes.py CircleTheorem -pqh
```

-pqh isn't necessary but it is quite helpful:

-p: Preview the video (opens automatically after rendering).
-q: Quality (possible values include l, m, h, p). q stands for low, medium, high, and production.
-h: Render in high quality (if you used -q h) or you can specify -q p for production quality.
