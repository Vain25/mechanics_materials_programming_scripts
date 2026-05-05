SymBeam: Statically Indeterminate Cable Solver

A symbolic structural analysis tool designed to solve for beam rotation and cable stay integrity. This script handles statically indeterminate systems where load distribution depends on material deformation.
Features

    Symbolic Mathematics: Supports both numeric inputs (e.g., 135000) and symbolic variables (e.g., w, L, E).

    Rigid Beam Analysis: Models the bridge as a rigid member rotating about a fixed pivot (Point B).

    Factor of Safety (FoS): Automatically calculates stress and compares it against A-36 structural steel yield strength.

    Indeterminate Solver: Uses the relationship between cable stretch and geometric rotation to find exact tensions.

Quick Start
    Install dependencies:
    PowerShell
    pip install numpy sympy
    Run the script:
PowerShell

    python statically_indeterminate_cable_solver.py

## Engineering Context
This tool is calibrated for the 45m bridge configuration described in `image_1e1b7d.jpg`. It uses consistent base units: **Newtons (N)** for force and **Meters (m)** for length.

*   **Standard Steel (A-36) Modulus:** `200e9` Pa
*   **Standard Steel (A-36) Yield:** `250e6` Pa

