# 1. Background

# What is RAM?

Radar Absorbing Materials reduce radar reflections by converting EM energy into heat.
A simple but effective RAM consists of:

1. A lossy dielectric layer, and

2. A metal backing (PEC) to block transmission.

3. The reflection from the surface is minimized when the material’s input impedance approaches free-space impedance.


# 2. Theory Summary
# Material Model

A lossy dielectric is expressed as:

# 𝜖=𝜖′−𝑗𝜖′′


# Chosen parameters:

1. Real permittivity (ε′): 8

2. Loss tangent (tanδ): 0.25

3. Thickness: 1–6 mm

# Absorption Calculation

Since transmission is zero (PEC backing):

# 𝐴=1−∣𝑅∣^2

# Transmission Line Approximation

A dielectric backed by PEC behaves like a short-circuited transmission line:

# 𝑍in=𝑗𝑍𝑑tan⁡(𝛽𝑑)
	​
Absorption peaks when:

# 𝑍in≈𝑍0
	​
	​
