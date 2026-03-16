
# FT1.1 — Sudoku Mathematical Model

Project: **Sistema Operador Unificador Fenomenológico General**

This package contains the formal description of the Sudoku mathematical model.

## Files

- **FT1_1_Sudoku_Model.pdf** — ready to publish paper
- **FT1_1_Sudoku_Model.tex** — LaTeX source
- **README.md** — project description

## Core Equation

S* = argmin_S [ Φ(S) + λ Σ_{x,y} |z_{k+1} - z_k| ]

Condition:

Φ(S) = 0

## Purpose

The model represents Sudoku as a 3D optimization system where:

- XY plane → board geometry
- Z axis → exploration depth
- Φ(S) → constraint validation

