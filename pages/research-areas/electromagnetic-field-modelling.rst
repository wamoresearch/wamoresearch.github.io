.. title: Electromagnetic Field Modelling
.. slug: electromagnetic-field-modelling
.. date: 2024-09-10 10:46:22 UTC+01:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text

==========
 Overview
==========

Predicting electromagnetic fields at high frequencies is of importance to –
among others –wireless communication technology and Electromagnetic
Compatibility (EMC). Field intensity simulations are difficult and time
consuming, hampered by (i) the need to resolve fields at the scale of the
wavelength – leading to small mesh sizes and thus large models, (ii) the
complexity of the environment and (iii) inherent uncertainty in setting up the
models. In the WAMO research group we apply asymptotic methods and Wigner
function approaches combined with random matrix theory to simulate
electromagnetic wave fields in the presence of intrinsic system complexity. The
research is done in close collaboration between the School of Mathematical
Sciences (Faculty of Science) and the George Green Institute for
Electromagnetics Research (Faculty of Engineering).


=================================
 Propagation of Wigner Functions
=================================

Predicting the properties of wave fields in complex environments is an extremely
challengingtask of crucial importance to a wide variety of technological and
engineering applications, such as vibro-acoustics or electromagnetic (EM) wave
modelling. In particular, characterizing the radiation of EM sources reliably,
both in free space and within enclosures, is a longstanding research issue. In
the context of electromagnetic compatibility (EMC), digital circuits and large
printed circuit boards (PCB) embed thousands of electronic devices and metallic
tracks and can produce fields reaching dangerous but hard-to-predict levels. We
therefore set out an approach for propagating such complex and statistically
characterized wave fields exploiting Wigner distribution function (WDF)
techniques. The WDF formalism offers a direct route to pure ray-tracing
approximations in an operator implementation, while still capturing in its exact
implementation the full wave dynamics. The formalism allows one to efficiently
treat radiation from complex sources, often having a statistical character.
Complexity arises here through the stochastic nature of the radiated field,
which may be best described by considering time or frequency averages and thus
looking at an ensemble of system realizations. A statistical representation is
then appropriate and computationally more efficient than a purely deterministic
treatment. Applications of the phase-space propagators include source
reconstruction and localization as well as emission source microscopy.

Related Publications
====================
- GRADONI, G., ARNAUT, L. R., CREAGH, S. C., TANNER, G., BAHARUDDIN, M. H., SMARTT, C. and THOMAS, D. W. P., June 2018. Wigner-Function-Based Propagation of Stochastic Field Emissions From Planar Electromagnetic Sources. IEEE Transactions on Electromagnetic Compatibility, Vol. 60, No. 3, pp. 580-588.
- GRADONI, G., RAMAPRIYA, D. M., CREAGH, S. C., TANNER, G., BAHARUDDIN, M. H., NASSER, H., SMARTT, C. and THOMAS, D. W. P., December 2017. Near-Field Scanning and Propagation of Correlated Low-Frequency Radiated Emissions. IEEE Transactions on Electromagnetic Compatibility, DOI: 10.1109/TEMC.2017.2778046.
- Propagating wave correlations in complex systems, S. C. Creagh, G. Gradoni, T. Hartmann and G. Tanner, Journal of Physics A 50, 045101 (2016)
- Measurement and Wigner Function Analysis of Field-Field Correlation for Complex PCBs in Near Field, M. Baharuddin, S. Greedy, D. W. P. Thomas, G. Gradoni, S. C. Creagh, G. Tanner, EMC Europe 2016, Wroclaw, Poland
- A Phase-Space Approach for Propagating Field-Field Correlation Functions Near Stochastic Sources, G. Tanner, G. Gradoni, and S. C. Creagh, EMTS2016, Espoo, Finnland
- A phase-space approach for propagating field-field correlation functions, G. Gradoni, S. C. Creagh, G. Tanner, C. Smartt, and D. W. Thomas, New J. Phys. 17 093027 (2015)
- C. Smartt ​et al., “​Challenges of time domain measurement of field-field correlation for complex PCBs​,” ​2015 IEEE International Symposium on Electromagnetic Compatibility ​ (EMC), Dresden, 2015, pp. 953-958.

===================================
 Near Field Wireless Communication
===================================

Substituting hard wiring between chips with wireless communications sustained
from antenna on-chip elements is a challenging new desing idea. Given the scale
of integration of modern electronics circuitry, wireless communications will
thenn take place at small scales, often implying that energy transport is
carried out in the near field. Understanding the impact of interference on the
performance of a multiple-input-multiple-output (MIMO) based device is of
paramount importance in ensuring that a proposed electronic design is both
resilient and robust. In this work and as part of the Horizon2020 Future
Emerging Technologies (FET) project Noisy Electromagnetic Fields for
Chip-to-Chip communication – `NEMF21
<https://web.archive.org/web/20200901202305/http://www.nemf21.org/>`_, the
effect of element-to-element interference in the creation of multiple channels
of a wireless link approaching the near-field regime is studied. Multiple
antenna transmit-and receive-arrays are considered for different antenna types
and arrangements operating between 5.6 and 60 GHz. In collaboration with
Tecnical University Munich, we find that multiple channels can be created even
if the antennas interact at sub-wavelength distances.

Related Publications
====================
- PHANG, S., IVRLAC, M. T., GRADONI, G., CREAGH, S. C., TANNER, G. and
  NOSSEK, J. A., February 2018. Near-Field MIMO Communication Links. IEEE
  Transactions on Circuits and Systems I: Regular Papers, Vol. 65, No. 9,
  3027-3036. DOI: 10.1109/TCSI.2018.2796305
- Analysis of a Near Field MIMO wireless channel using 5.6 GHz dipole antennas’,
  Mohamed Ismaeel Maricar, Gabriele Greadoni, Steve Greedy, Michel T Ivrlac,
  Josef A Nossek, Gregor Tanner and Dave Thomas. ESA Workshop on aerospace EMC,
  May-2016, Valencia, Spain

=========================================================
 DEA and wireless communications in complex environments
=========================================================

At millimetre wave (mmWave) frequencies, that is at tenth of GHz, full wave
electromagnetic simulations become computationally expensive and classical ray
tracing algorithms, e.g., shoot and bounce schemes, converge slowly to the
solution. Phase-space methods developed at WAMO such as the Dynamical Energy
Analysis (DEA) are used to perform ray-tracing calculations in large, complex
environments and thus provide the right tool for the telecommunication industry
to plan network coverage on the vast scales needed. For applications in
electromagnetics, DEA has been extended to three dimensional spaces and
including polarisation. The formulation of a physics-based outdoor-to-indoor
transfer function is tackled using efficient methods based on random matrix
theory and transfer operator approaches. We are working on predicting the EM
energy flow through multiply-connected and complex environments by a fusion of
the Random Coupling Model (RCM) with DEA. Applications are envisaged in the
telecommunication industry, naval environments and avionics. This project is
funded by Telecom Italia Lab, Italy and the Office of Naval Research (ONR), USA.

Related Publications
====================
- H. Nasser et al., “High frequency propagation in large and multiply connected
  electromagnetic environments,” 2016 IEEE Metrology for Aerospace
  (MetroAeroSpace), Florence, 2016, pp. 342-347. [BEST CONFERENCE POSTER PAPER
  AWARD]

=========================================================================
 Transmission Lines, Quantum Graphs and Fluctuations on Complex Networks
=========================================================================

High-frequency cables connecting electronic devices and sensors can form
intricate networks. Modelling the propagation of signals through these cable
networks in the presence of parameter uncertainty, is a challenging task. We
study the response of high-frequency cable networks using both Transmission Line
and Quantum Graph (QG) techniques. We have successfully compared the two theorie
with measurements on real, lossy cables. We have derived a generalisation of the
vertex scattering matrix to include non-uniform networks – networks of cables
with different characteristic impedances and propagation constants. The QG model
implicitly takes into account the pseudo-chaotic behaviour of the propagating
electric signal. The asymptotic growth of eigenvalues of the Laplacian can e
predicted using Weyl’s law and the nearest-neighbour level-spacing distribution
of the resonances are compared with predictions of Random Matrix Theory (RMT).
The problem of scattering from networks of cables can also provide an analogue
model for wireless communication in highly reverberant environments. In this
context we provide a preliminary analysis of the statistics of communication
capacity for communication across cable networks. The aim is to enable detailed
laboratory testing of information transfer rates using software defined radio
for MIMO (Multiple-Input Multiple-Output) protocols.

==============================
 Statistical Electromagnetics
==============================

Electromagnetic propagation within complex, confined systems can be
characterized through statistical methods. The assumptions underneath those
methods are similar to those adopted in statistical physics for a gas of
non-interacting particles confined in a box. In electromagnetics, the energy can
be thought as propagated by a “gas’’ of interfering partial waves and thus
modelled by a Plane Wave Expansion (PWE). The complexity of the system, e.g.,
uncertain and/or irregular boundaries of a cavity, is thus captured in the
statistics of partial wave phase, amplitude, correlation and direction of
propagation, from which total field statistics can be derived through entropy
maximisation methods. An alternative is modelling cavity fields as a
superposition of ergodic eigen-modes with random modal coefficients and resonant
frequencies. The former can be tackled again with a random uncorrelated PWE,
also known as Berry’s hypothesis. The latter offers an interesting connection
with universal laws predicted by the RMT for the eigen-energies of chaotic
systems. Researchers of the WAMO have contributed to establish those approaches
and explain numerical and experimental observations on higher order energy
statistics, quality factor and coherence bandwidth probability distributions, as
well as extreme value field statistics of electromagnetic reverberation
chambers. Electromagnetic reverberation, born for performing robust and extreme
tests in electromagnetic compatibility and recently used to emulate indoor and
outdoor wireless environments, is now transitioning to become part of
statistical physics. Current research efforts are dedicated to:
- understanding the number of uncorrelated chamber realizations,
- creating a physical model for the chamber lowest usable frequency,
- studying dynamical effects associated with electromagnetic reverberation,
  including Fermi acceleration, Doppler shift, transient eigen-modes and
  diffusion.



Related Publications
====================
- GRADONI, G., RUSSER, J., BAHARUDDIN, M. H., HAIDER, M., RUSSER, P., SMARTT, C., CREAGH, S. C., TANNER, G., and THOMAS, D. W. P., 2018, Stochastic Electromagnetic Field Propagation – Measurement and Modelling, Special Issue on Celebrating 125 years of Oliver Heaviside’s ‘Electromagnetic Theory’: physical and engineering science papers and historical perspectives, Royal Society Philosophical Transactions A, in press.
- M. Migliaccio, G. Gradoni and L. R. Arnaut, “Electromagnetic Reverberation: The Legacy of Paolo Corona,” in IEEE Transactions on Electromagnetic Compatibility, vol. 58, no. 3, pp. 643-652, June 2016
- L. R. Arnaut and G. Gradoni, “Probability Distribution of the Coherence Bandwidth of a Reverberation Chamber,” in IEEE Transactions on Antennas and Propagation, vol. 63, no. 5, pp. 2286-2290, May 2015.
- G. Gradoni and L. R. Arnaut, “Transient evolution of eigenmodes in dynamic cavities and time-varying media,” in Radio Science, vol. 50, no. 12, pp. 1256-1270, Dec. 2015.
- G. Gradoni, V. Mariani Primiani, and F. Moglie, “Reverberation chamber as a multivariate process: FDTD evaluation of correlation matrix and independent positions,” Progress In Electromagnetics Research, Vol. 133, 217-234, 2013.
- L. R. Arnaut and G. Gradoni, “Probability Distribution of the Quality Factor of a Mode-Stirred Reverberation Chamber,” in IEEE Transactions on Electromagnetic Compatibility, vol. 55, no. 1, pp. 35-44, Feb. 2013.
- Gradoni, G. and Arnaut, L.R., “Minimum-value distribution of random electromagnetic fields for modeling deep fading in wireless communications,” Ann. Telecommun. (2011) 66: 465.
- G. Gradoni and L. R. Arnaut, “Generalized Extreme-Value Distributions of Power Near a Boundary Inside Electromagnetic Reverberation Chambers,” in IEEE Transactions on Electromagnetic Compatibility, vol. 52, no. 3, pp. 506-515, Aug. 2010.
- G. Gradoni and L. R. Arnaut, “Higher Order Statistical Characterization of Received Power Fluctuations for Partially Coherent Random Fields,” in IEEE Transactions on Electromagnetic Compatibility, vol. 51, no. 3, pp. 583-591, Aug. 2009.
