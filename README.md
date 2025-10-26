# Molecular-dynamics
This repository contains LAMMPS molecular dynamics simulation codes for studying mechanical behaviors, including uniaxial loading, cyclic loading, crack propagation, rigid-body impact, and shockwave impact. Some key parts have been removed or modified, but I can provide the full code upon request—please contact me via email if needed.

First, it should be noted that single crystals can be modeled directly in LAMMPS in most cases, whereas polycrystals require modeling with external software such as Atomsk. I highly recommend using Atomsk for modeling, as it is beneficial for setting up detailed structural models.

[Single_crack] is an MD simulation of crack propagation in a nickel single crystal, with detailed comments in Chinese. It can serve as one of the best starting points for learning molecular dynamics.
Professor Bin Shan from Huazhong University of Science and Technology has provided a detailed tutorial video on Bilibili (BV1amyzYJEYE).

[in.uniaxial_load.lmp] is an MD script that simulates uniaxial loading. By controlling the sign of the applied load, it can perform either tension or compression. The script incorporates a von Mises distribution and can output the corresponding stress–strain curve.
