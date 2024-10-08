# Introduction of the open-source numerical tool QNM-ED-LD for an efficient electrodynamics (ED) Langevin-dynamics (LD) simulation of multiple nanoparticles based on the coupling theory of quasinormal mode (QNM)
In reference [1] we propose an efficient method for simulating the motion of multiple nanoparticles under light-field excitation. In this method abbreviated as QNM-ED-LD, by exploiting the method proposed in reference [2] based on the coupling theory of quasinormal mode (QNM) [3] for an efficient electrodynamics (ED) calculation of optical force of multiple nanoparticles, one can achieve a fast solving of the Langevin dynamics (LD) equation which governs the motion of multiple nanoparticles and comprehensively incorporates the influence of optical force, viscous resistance, Brownian motion and the electrostatic double-layer force between particles. This method is generally applicable to any incident light beam and any geometries of nanoparticles. Compared with the ED-LD method based on full-wave finite element method (FEM) for calculating optical force (abbreviated as FEM-ED-LD), this method can reduce the computation time by at least two orders of magnitude. This method can be used as an efficient tool for designing optical tweezers with various applications.

In reference [1], as a numerical example, this method is used to simulate the motion of 40nm-radius spherical gold particles excited by a tightly focused laser beam of linear or radial polarization. In the simulation, gold particles move within a two-dimensional plane determined by the substrate surface. The refractive index of the substrate can be either the same as that of the water environment [as shown in Fig. 5(b1)] or different (as shown in Fig. S8, where the substrate is glass and the distance between the gold particles and the substrate is fixed). With minor modifications, this open-source numerical tool can be used for a fast simulation of the motion of particles in three-dimensional free space.

As typical numerical examples in reference [1], the codes for generating all curves in Fig. 5(b1) and Fig. S8 are provided in folders named "Fig5(b1)" and "FigS8", respectively, including the codes of QNM-ED-LD and FEM-ED-LD. The method for using the codes can be found in Section 3 "Instructions for Using the QNM-ED-LD Tool" of the file "Read me.pdf".

# The softwares used by the QNM-ED-LD tool
The QNM-ED-LD open-source numerical tool uses COMSOL Multiphysics software (version 6.1) to calculate QNMs and the background field of focused laser beam, and uses MATLAB software (via COMSOL LiveLink for MATLAB, i.e. COMSOL with MATLAB) for electromagnetic-field and optical-force calculations as well as particle-motion simulations.

# Citing QNM-ED-LD
We kindly request that you cite the following Refs. [1-3] in any published work for which you used our provided codes here.

# References
[1] Lu, X.; Tao, Q.; Zhong, Y.; Liu, H. Efficient method for the electrodynamics Langevin-dynamics simulation of multiple nanoparticles based on the coupling theory of quasinormal mode. ACS Photonics 2024, 11 (8), 2970-2980.

[2] Qi, Z.; Zhong, Y.; Liu, H. Efficient method for the calculation of the optical force of multiple nanoparticles based on the coupling theory of quasinormal modes. Opt. Lett. 2021, 46 (18), 4610-4613.

[3] Tao, C.; Zhu, J.; Zhong, Y.; Liu, H. Coupling theory of quasinormal modes for lossy and dispersive plasmonic nanoresonators. Phys. Rev. B 2020, 102 (4), 045430.
