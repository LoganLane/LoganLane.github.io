---
title: "GPU-Accelerated 3D UI Layout Optimization"
excerpt: "A high-performance pipeline for exhaustive evaluation of 3D user interface layouts using CUDA parallelization and predictive human performance models.<br/><img src='/images/layout_optimization.png'>"
collection: portfolio
---
**Developed in collaboration with [Ben Tatum](https://www.linkedin.com/in/btatum26/)**

<iframe width="640" height="360" 
  src="https://www.youtube.com/embed/ucV9BI6wS_E" 
  frameborder="0" allowfullscreen>
</iframe>

As part of my dissertation research on predictive modeling of human performance for 3D user interfaces, I developed a pipeline that uses GPU parallelization to exhaustively evaluate large numbers of candidate 3D UI layouts. The system applies predictive models — including Fitts' law extensions for 3D interaction tasks — to score layouts based on estimated task completion time across a wide range of user configurations.

The backend uses CUDA to parallelize evaluation across billions of layout candidates, with a Python/FastAPI layer exposing results to a Unity frontend for visualization. DuckDB serves as the analytical backend for querying evaluation results. The goal is to move beyond manual, intuition-driven UI design toward empirically-grounded, model-driven layout optimization for XR interfaces.

**Stack:** Python, CUDA, FastAPI, DuckDB, Unity, C#
