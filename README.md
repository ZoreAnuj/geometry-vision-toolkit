# Geometry Vision Toolkit

A Rust library for 2D and 3D geometric transformations, tailored for computer vision and robotics applications. It provides a robust foundation for handling rotations, poses, and coordinate frames, enabling precise and efficient spatial reasoning.

## Key Features
*   **Lie Group Operations:** Implements SO(2), SO(3), SE(2), and SE(3) for rotations and rigid body transformations.
*   **Interpolation & Optimization:** Supports SLERP for smooth interpolation and provides utilities for on-manifold optimization.
*   **Jacobian Computation:** Calculates analytical derivatives for integration with non-linear solvers and estimators.
*   **Pose Graph & Bundle Adjustment:** Core components for building and solving spatial constraint problems.

## Tech Stack
*   **Language:** Rust
*   **Key Dependencies:** `nalgebra` (linear algebra), `num-traits` (numeric traits), `approx` (floating-point comparisons)

## Getting Started
Add the library to your `Cargo.toml`:
```toml
[dependencies]
geometry-vision-toolkit = "0.1"
```
Import and use the modules in your code:
```rust
use geometry_vision_toolkit::se3;
```