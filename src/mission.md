## Center Mission

The engineering of plasmas is more difficult than the engineering of other states of matter:
plasmas have many more mechanisms through which to actively redistribute energy to arrive at states preferential to the plasma -- regardless of engineering constraints.
The solution space for transport equations coupled to Maxwell’s equations is rugged terrain with significant cliffs, peaks, and valleys that
correspond to these many nonlinear transitions (instabilities).
Further complicating the design/control process is the fact that the plasma is a dynamical system with rich intermittent and chaotic behaviors,
which manifest as an additional source of uncertainty in plasma responses.

We need to develop kinetically aware, fast surrogate models for decision and active control in  plasma applications.
Robustness to CME events could be enhanced if we could make mitigation deployment decisions within the short window of time between the detection of a CME and its arrival at Earth.
Of course, such decisions will require quantified confidence levels, since the cost of a mistake could be in the billions of dollars.
Inertial Fusion Energy (IFE) power-plant concepts currently rely on fast repetition-rate lasers, with target implosions at 1-10 Hz (vs. sub-mHz frequencies of current Inertial Confinement Fusion (ICF) experiments).
Given the need for mass-produced targets, active adjustment of the energy delivery (pulse amplitude, duration, shape, etc.) will be necessary to accommodate defects in the targets, requiring rapid assessment of the implosion efficiency and automated changes in the driver.
In Magnetic Fusion Energy (MFE), tokamak detachment and disruption mitigation strategies require active control, especially for the latter, where the disruption can occur on tens of millisecond time scales.
Uncontrolled plasma disruptions (and the ensuing generation of fast electrons) can cause reactor damage in the  millions of dollars and result in significant down-time, so sophisticated plasma-response surrogates  with quantified bias/uncertainty would significantly advance the state of the art in active control for MFE.

To focus our efforts, we will consider two target applications with the dual goal of integrating the thrust developments throughout the project, and providing a demonstration test-bed for mathematical breakthroughs.

## Runaway electrons in MFE

Runaway electrons (RE) form as the plasma in a tokamak cools during the thermal quench stage in a disruption due to enhanced plasma resistivity and the corresponding increase of the induced loop voltage. 
Once they break free from collisional drag, REs become fundamentally kinetic since they cannot be controlled by self-collisional processes. 
As they accelerate, REs may pick up an increasing fraction of the plasma current, affecting magnetic field evolution. REs are confined by nested flux surfaces in a tokamak and can accelerate to sufficiently large energies to eventually rupture the vacuum wall, which is a key obstacle for the prospects of MFE as an energy source.
Understanding RE generation and dynamics is a phenomenal applied mathematics challenge, in principle requiring the integration of the high-dimensional relativistic Vlasov-Fokker-Planck (VFP) equation over magnetohydrodynamic (MHD) timescales (much longer than electron collision and transit times). The ultimate goal is to understand magnetic field evolution in the presence of an evolving RE population and how to affect it to prevent RE formation and acceleration. Addressing this challenge will require the tools proposed in CHaRMNET, including hierarchical multiscale methods, data-driven surrogates, and MF approaches for control and UQ (to identify suitable mitigation strategies at the engineering scale). 


## Nonequilibrium hohlraum physics (NHP) for ICF/IFE

The National Ignition Facility ignited a laser-driven compressed fusion fuel capsule in August, 2021. While momentous, this outcome has not yet been reproduced. Achieving reproducible ignition is critical for ICF National Security purposes and for the long-term prospects of IFE.
The largest source of uncertainty in current modeling capabilities is the hohlraum, a cylindrical device that encloses the capsule containing the fusion fuel, that transforms laser energy into X-ray energy that bathes and compresses the capsule. Lack of irradiation uniformity leads to capsule implosion degradation, critically impacting the prospects for ignition.
Maximizing radiation uniformity is therefore critical, which can be cast as an optimal-design-under-uncertainty problem.
Addressing this challenge requires modeling both kinetic plasmas and radiation fields, coupled with lasers in realistic geometries. This problem is a second phenomenal applied mathematics challenge, with important ramifications for national security and the attainment of fusion energy on Earth, that touches on all of CHaRMNET's themes.

