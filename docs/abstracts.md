---
layout: default
title: ABIDEV 2026
tagline: ABIDEV 2026
description: 12th International ABINIT Developer Workshop <br> Sant Feliu de Guixols, Catalonia, Spain, 8-11 June 2026
---
[Home](index.md) | [Program](program.md) | [Abstracts](abstracts.md) | [Registration](registration.md) | [Practical information](practical.md) | [Organizing committee](organizing.md)
<hr>

# Invited talks

 <a id="Artacho"></a>
### Electron dynamics in solids - from electronic stopping to quantum kicks
#### Emilio Artacho, Nanogune and University of Cambridge, Spain
An overview will be presented on our work describing far-from-equilibrium processes in solids using real-time time-dependent density-functional theory. Motivated by radiation damage of matter, there is interest in the process of transfer of energy to the electrons in matter from the kinetic energy of a nuclear projectile shooting through it, a dissipative process of both fundamental and applied interest. Apart from showing first-principles results for the electronic stopping power (energy transfer rate) and their agreement with experiments, I will focus rather on technical aspects. In particular, our using atomic orbitals as basis sets (unlike Abinit), has prompted a differential geometry formalisation of the equations arising for the evolution and the Ehrenfest forces which could be useful in other contexts, possibly around Abinit as well. Finally I will describe the consequences of an exact relation for the excess energy acquired by a quantum system when suddenly starting a constant-velocity motion of the external potential (a kick). It also connects with the need to redefine pseudopotentials when they move and its consequences.
<br><br>

<hr>
 <a id="Buonaura"></a>
### Theoretical Modeling of Ultrafast Phase Transitions from the Femtosecond to the Picosecond Scale 
#### Matteo Calandra Buonaura, University of Trento, Italy
In this talk, I will introduce a theoretical approach to ultrafast phase transitions that captures both electron/hole and phonon dynamics following laser pumping, on time scales ranging from a few femtoseconds to several picoseconds after irradiation.

At short times, the method relies on solving the Bloch equations coupled to Ehrenfest dynamics. It includes the electric field of the pump explicitly, as well as carrier-carrier, carrier-phonon, and phonon-phonon scattering, treated entirely from first principles.

At longer times before recombination, when carrier-carrier interactions generate a photoexcited quasi-equilibrium electron-hole plasma, the approach is based on a constrained density-functional perturbation theory (cDFPT) scheme that accounts for the presence of holes in the valence band and electrons in the conduction band (two-Fermi-level approach). In this framework, the calculation of forces, phonon dispersion, and carrier-phonon coupling becomes possible, as well as molecular dynamics with machine-learning potentials in the presence of an electron-hole plasma.

I will showcase applications of the method to several materials.

This work is funded by the European Union (ERC, DELIGHT, 101052708).


<br><br>

<hr>
 <a id="Catalan"></a>
### About flexoelectricity in conducting and/or polar materials preconceptions and few answers about flexoelectricity in conducting and/or polar materials
#### Gustau Catalan, ICREA and ICN2, Catalonia
Flexoelectricity is defined as the generation of polarization by strain gradients, and it is a universal property of materials. Though initially seen as a way to induce polarization in non-polar dielectrics such as SrTiO3, flexoelectricity has broadened its range to semiconductors and even metals, as well as materials that are already polar such as ferroelectrics. This new wave of flexoelectric research has seen flexoelectricity couple with already existing properties (e.g. photovoltage in semiconductors) or generate new ones (e.g. polarization vortices in metals). Some of these recent results challenge established preconceptions about the very meaning of some fundamental concepts, e.g. can one talk about polarization in a metal? How do we even quantify it? In my talk, I would like to discuss some of our work in this “new wave” of flexoelectric research (flexoelectric metals, flexphotovoltaic effects in semiconductors, second harmonic flexoelectricity in ferroelectrics), hoping to inspire some critical discussions. 
<br><br>

<hr>
 <a id="Draxl"></a>
### Data quality assessment through benchmarking and machine learning
#### Claudia Draxl, HU Berlin, Germany
Validation and verification of research data is becoming more in more important, in particular in view the reuse of data by machine learning and other artificial-intelligence tools. For this purpose, also benchmark data are highly desirable for assessing the relevance of various parameters in scientific results. For the computational side, this concerns the impact of methodology, approximations, implementations, and computational details on the results. We are addressing this issue by creating various dedicated benchmark sets for groundstate calculations within density-functional theory and spectroscopy calculations within many-body perturbation theory. These calculations are predominantly, but not exclusively, with electronic-structure package exciting [1,2]. Being an all-electron full-potential code with proven microHartree precision [3], exciting is able to deliver such data. To quantitatively measure data quality, we have developed various machine-learning techniques [4,5] and have defined metrics also for spectroscopic quantities [6,7]. 

In this talk, I will give an overview of our benchmarking studies and efforts towards error quantification. I will also discuss how other codes – like Abinit – could contribute to and benefit from this effort.

[1] A. Gulans, S. Kontur, C. Meisenbichler, D. Nabok, P. Pavone, S. Rigamonti, S. Sagmeister, U. Werner, and C. Draxl, J. Phys.: Condens. Matter (Topical Review) 26, 363202 (2014)
[2] https://arxiv.org/abs/2601.11388
[3] A. Gulans, A. Kozhevnikov, and C. Draxl, Phys. Rev. B 97, 161105(R) (2018).
[4] T. Bechtel, D. Speckhard, J. Godwin, and C. Draxl, Chem. Mater. 37, 1358 (2025).
[5] D. Speckhard, C. Carbogno, S. Lubeck, L. Ghiringhelli, M. Scheffler, and C. Draxl, Phys. Rev. Materials 9, 013801 (2025).
[6] M. Kuban, S. Rigamonti, M. Scheidgen, and C. Draxl, Sci. Data 9, 646 (2022).
[7] M. Kuban, S. Gabaj, W. Aggoune, C. Vona, S. Rigamonti, and C. Draxl, MRS Bulletin Impact 47, 991 (2022).
<br><br>

<hr>
 <a id="García"></a>
### Perspectives on Siesta development within the MaX project and connections to Abinit
#### Alberto García, ICMAB-CSIC, Spain
Siesta is one of the flagship codes of the Materials at the eXascale (MaX) EU project, which aims at enabling the use of materials simulation tools in next-generation HPC systems. I will discuss  the main areas in which participation in MaX has been instrumental in the development of Siesta. Besides its work on MaX-specific codes, the project aims to transfer expertise and tools to the broader community, something Abinit is well-placed to benefit from.

One of the core ideas of MaX, that code modularization and separation of concerns is the key to progress, goes back to the principles of the Electronic Structure Library, of which the Siesta and Abinit communities are founding partners and contributors. I will show how this collaboration continues and will call for fresh ideas to address the coming challenges.
<br><br>

<hr>
 <a id="Royo"></a>
### Linear response of magnets from constrained DFPT
#### Miquel Royo, ICMAB-CSIC, Spain<br>Coauthor(s): Massimiliano Stengel
Accurate calculation of the linear response of magnetic systems requires careful treatment of nonadiabatic spin-phonon coupling in time-reversal-broken environments. Existing approaches rely on semiclassical magnon descriptions, lacking a transparent connection to first-principles frameworks such as time-dependent DFT. Furthermore, time-dependent DFPT calculations for noncollinear spin systems are notoriously difficult to converge, as low-energy magnons severely worsen the condition number of the underlying linear problem.
In this talk, I present a methodological framework recently implemented in ABINIT that addresses these challenges by parametrically constraining atomic magnetic moments to their unperturbed ground-state values during frequency-dependent linear-response calculations. Optimal convergence is achieved through a penalty-function approach, while the physically meaningful relaxed-spin response functions are recovered via straightforward linear-algebra operations derived from a Legendre transform formalism, as implemented in ANADDB. I will further demonstrate how this framework enables efficient first-principles calculation of material-specific spin-phonon coupling coefficients, and provides a natural foundation for studying coupled spin-phonon dynamics.
<br><br>

<hr>
 <a id="Souza"></a>
### Optical spatial dispersion via Wannier interpolation
#### Ivo Souza, Centro de Física de Materiales, Universidad del País Vasco, Spain<br>Coauthor(s): Andrea Urru, Óscar Pozo Ocaña, Stepan Tsikin, David Vanderbilt
Wannier functions give an "exact" tight-binding representation of the
low-energy ab initio electronic structure, providing a fast and
accurate k-space interpolation scheme.  In addition to band
dispersions, Wannier interpolation has been successfully applied to
computate Berry curvatures, orbital magnetization, and
magneto-optical spectra. I will review the basic ideas, and describe a
recent extension to optical spatial dispersion effects such as natural
optical activity and directional dichroism.
<br><br>


# Contributed talks

<hr>
 <a id="Allemand"></a>
### Iterative solution of the Boltzmann Transport Equation for (magneto-) thermoelectric transport
#### Guillaume Allemand, University of Liège, Belgium
We want to study charge and heat transport from first-principles in topological Weyl semimetals such as TaAs. Electron-Phonon Coupling (EPC) matrix elements are calculated using the~\textsc{ABINIT} software suite, performing Density Functional Perturbation Theory (DFPT), and used to derive the thermo-electric transport coefficients,  including the electrical conductivity ($\sigma$), Seebeck coefficient ($S$), electronic thermal conductivity (${\kappa}^{el}$).
We compare the Self-Energy and Momentum Relaxation Time Approximations (SERTA and MRTA) to the Iterative solution of the Boltzmann Transport Equation (IBTE).
For the iterative method, there was a lack of software treating the thermal part of the BTE. Consequently, we derived and implemented in Abinit an additional equation, which is needed to fully solve for transport under both thermal and electrical potential gradients.
Moreover, we are currently trying to implement the BTE considering also a magnetic field, leading to the apparition of Hall and Nernst effects. Unfortunately, the implementation is not trivial, since the addition of a magnetic field breaks symmetries, such as time-reversal symmetry and some spatial symmetries.
<br><br>

<hr>
 <a id="Antonius"></a>
### Recent developments in aTDEP
#### Gabriel Antonius, Université du Québec à Trois-Rivières, Canada
I will present recent development in the aTDEP utility for the computation of anharmonic phonons. Modernization of the CLI interface and and input file format. Interface with Abinit and Anaddb through DDB files. Integration to the Abipy environment.
<br><br>

<hr>
 <a id="Baguet"></a>
### Abinit ground-state performances on CPUs
#### Lucas Baguet, CEA Bruyères-le-Châtel, Université Paris-Saclay, France
Abinit offers numerous parameters to control the performance of ground state computations. Users must select from various algorithms, levels of parallelization, and parameters that influence convergence rates. Additionally, recent developments have enhanced the performance of ground state computations by introducing new implementations and algorithms. However, the current default parameters and automatic parallelization rules may now be outdated.
<br><br>

<hr>
 <a id="Barat"></a>
### Preconditioning Magnetic systems in ABINIT
#### Clémentine Barat, CEA Bruyères-le-Châtel, Université Paris-Saclay, France
The convergence of the self-consistent field in Kohn-Sham DFT can significantly degraded by small eigenvalues in the dielectric matrix. These small eigenvalues often arise from magnetic phase transitions. We will present such convergence challenges in detail and introduce a new preconditioning scheme to address them. Our approach, implemented in Abinit, draws inspiration from the Stoner model and is based on a non-interacting susceptibility that neglects inter-orbital interactions.
<br><br>

<hr>
 <a id="Bastogne"></a>
### 2nd-Principles Models in MULTIBINIT: Availability and Applications
#### Louis Bastogne, University of Liège, Belgium<br>Coauthor(s): Fernando Gomez, He Xu, Philippe Ghosez
Second-principles lattice dynamics, as implemented in Multibinit, has become a powerful route to reach the large length and time scales needed to study finite-temperature properties of functional materials while retaining first-principles accuracy. The total energy is expanded around a reference structure combining all the lattice degrees of freedom. Building such effective models, however, has long required substantial expertise and manual effort.
Here we present recent advances that make the construction of lattice models both automatic and reliable. While the harmonic part is obtained directly from first-principles calculations, the more demanding anharmonic part is now built through a fully automated workflow that handles the training, fitting, and stabilization of the model with minimal user input. The user only needs to specify a few high-level choices, such as how far interactions extend and how complex the model should be, and the procedure takes care of the rest.
Each model is validated through a systematic validity passport: reproduction of the training and test sets, relaxation of metastable phases, and phonon dispersion curves of the (meta-)stable phases, ensuring transferability before release.
Beyond automation, we emphasize availability: validated models are being released in an open, citable library (Dataverse) and exposed through Python and LAMMPS interfaces, so the community can directly reuse them. We illustrate their reach across applications: structural phase transitions under pressure and strain; finite-temperature functional properties; inhomogeneous textures such as domain walls and topological or multimodal states; and temperature-dependent phonon.
<br><br>

<hr>
 <a id="Béjaud"></a>
### Machine Learning Assisted Sampling Package
#### Romuald Béjaud, CEA Bruyères-le-Châtel, Université Paris-Saclay, France
Ab initio molecular dynamics (AIMD) simulation is a powerful tool to predict material properties at finite temperatures but is computationally expensive. To address this issue, we introduce the machine learning assisted canonical sampling (MLACS) method, which accelerates the sampling of the Born-Oppenheimer potential energy surface. Based on a self-consistent variational procedure, MLACS iteratively trains a machine learning interatomic potential (SNAP, MTP, ACE, or GrACE) and generates a canonical distribution of positions that mimics the AIMD distribution. By proving the reliability of the method on weak and strong anharmonic systems, for both solid and liquid, we show that MLACS reduces by several orders of magnitude the high computational cost of AIMD while maintaining an ab initio accuracy. Additionally, we reused the main idea of MLACS to apply it to other ab initio procedures, such as atomic relaxations, energy path calculations, grand canonical sampling, and path integral molecular dynamics.
<br><br>

<hr>
 <a id="Blanchet"></a>
### Thermal exchange-correlation functionals support
#### Augustin Blanchet, CEA Bruyères-le-Châtel, Université Paris-Saclay, France<br>Coauthor(s): Marc Torrent, Valentin V. Karasiev
Although KS-Mermin-DFT has proven to be successful in handling the warm dense matter regime (identified for temperatures $T \approx E_\mathrm{F}/k_\mathrm{B}$), numerical and conceptual difficulties must be addressed when running simulations at such temperatures. Indeed, the Fermi-Dirac distribution forces us to consider many more bands than are initially needed at 0\,K, along with the frozen-core approximation, which must be adapted when core states begin to be thermally ionized. Additionally, the usual exchange-correlation functionals we use (PW, PBE, ...) do not depend explicitly on the electronic temperature. Cold functionals induce maximum errors in the WDM regime [1].

Over the last few years, some progress has been made by taking into account the explicit temperature dependance of the xc functionals, parametrized using path-integral Monte-Carlo calculations. These thermal xc functionals (a.k.a. free energy xc functionals) can either be based on the local density approximation [2], or the generalized gradient approximation [3]. Unlike cold xc functionals, LibXC does not yet fully support free energy xc functionals, and each DFT software package must be adapted to explicitly treat an exchange-correlation entropy term in order to properly obtain the internal energy of the system.

Abinit now fully supports thermal exchange-correlation functionals, with two new native options: KSDT (thermal LDA) and KDT16 (thermal GGA). The interface is also ready for future versions of LibXC, which will return the xc entropy contribution.

[1] V. V. Karasiev, L. Calderı́n, and S. B. Trickey. Importance of finite-temperature exchange correlation for warm dense matter calculations. 93(6):063207.<br />
[2] V. V. Karasiev, J. W. Dufty, and S. B. Trickey. Nonempirical Semilo-cal Free-Energy Density Functional for Matter under Extreme Conditions. 120(7):076401.<br />
[3] V. V. Karasiev, T. Sjostrom, J. Dufty, and S. B. Trickey. Accurate Homo-geneous Electron Gas Exchange-Correlation Free Energy for Local Spin-Density Calculations. 112(7):076403.
<br><br>

<hr>
 <a id="Boust"></a>
### Relaxed core PAW / Finite-temperature GWR
#### James Boust, CEA Bruyères-le-Châtel, Université Paris-Saclay, 
In this talk, I will discuss two unrelated topics.

First, I will motivate the implementation of the core relaxation in PAW (RC-PAW) for matter in extreme conditions.
I will benchmark the newly developped RC-PAW approach in Abinit and apply it on aluminium and molybdenum.

Second, I will give an overview of the current status of the GW code in real-space (GWR) for the specific case of non-zero temperatures.
I will focus on the implementation in Abinit of optimized imaginary time/frequency grids -- minimax and discrete Lehmann representation.
<br><br>

<hr>
 <a id="Brieuc"></a>
### Advances regarding real-time TDDFT
#### Fabien Brieuc, CEA Bruyères-le-Châtel, Université Paris-Saclay, France
This talk will present recent updates on the implementation of real-time TDDFT in Abinit. It will focus on the implementation of the method within the projector augmented wave (PAW) approach in the presence of a time-dependent external electric field.
<br><br>

<hr>
 <a id="Fiorazzo"></a>
### Vibrational natural optical activity in crystals
#### Chiara Fiorazzo, ICMAB-CSIC, Spain<br>Coauthor(s): Asier Zabalo, Miquel Royo, Ivo Souza, Massimiliano Stengel
We present a general first-principles framework for vibrational natural optical activity in periodic systems. Existing approaches within density-functional theory are well established for molecules, but cannot be directly extended to crystals because they are incompatible with translational invariance. Our formulation overcomes this limitation by expressing vibrational optical activity as a spatial-dispersion response property, naturally compatible with periodic boundary conditions.

The formalism applies directly to crystalline systems, while recovering the established molecular limit. All required quantities are computed within the longwave driver of Abinit, enabling a straightforward implementation. The framework clarifies the role of periodicity in the electromagnetic response and provides an interpretation of vibrational optical activity in terms of finite-momentum absorption.

We demonstrate the approach through first-principles calculations of the vibrational circular dichroism of the chiral molecular and crystalline systems D$_2$-oxirane and $\alpha$-quartz.
<br><br>

<hr>
 <a id="Gendron"></a>
### DMFT in ABINIT: Recent advances and applications
#### Frédéric Gendron, CEA Bruyères-le-Châtel, Université Paris-Saclay, France<br>Coauthor(s): Emmanuel Castiel, Bernard Amadon
In this presentation we will discuss the extension of the CT-QMC solver in Abinit in order to handle complex hybridization functions.
<br><br>

<hr>
 <a id="Giantomassi"></a>
### Electron-phonon coupling using GW perturbation theory
#### Matteo Giantomassi, UCLouvain, Belgium
The interaction between electrons and phonons governs a wide range of fundamental material properties,  including electrical and thermal transport, superconductivity, and the temperature dependence of electronic band structures. 
Traditionally, electron–phonon matrix elements are computed within Density Functional Perturbation Theory (DFPT), which relies on the first-order variation of the Kohn–Sham potential. 
While highly successful, this framework is fundamentally limited by its independent-particle description and therefore neglects important many-body effects.

In this talk, I will present our implementation of GW Perturbation Theory (GWPT), originally proposed by Z. Li and co-workers in 2019,  within the ABINIT software package. 
By directly evaluating the first-order variation of the GW self-energy with respect to atomic displacements,  GWPT extends the DFPT formalism to include many-body corrections to electron–phonon interactions within a unit-cell framework.

I will discuss both the theoretical foundations of the method and the computational infrastructure developed to address its substantial computational cost. 
In particular, I will present the integration of GWPT with the gstore API, 
which enables the efficient pre-computation, distributed MPI storage, and NetCDF-based storage of Kohn–Sham and GWPT matrix elements,  providing a practical route toward large-scale many-body electron–phonon calculations.
<br><br>

<hr>
 <a id="Gingras"></a>
### Strong correlations in ABINIT: Interface to triqs_modest (MODular Electronic STructure package)
#### Olivier Gingras, Flatiron Institute, USA
_No abstract_
<br><br>

<hr>
 <a id="Ortiz"></a>
### Time-dependent and spatially inhomogeneous electric fields in Multibinit and perspectives for coupled lattice–electronic simulations
#### Fernando Gómez Ortiz, University of Liège, Belgium
Recent developments in Multibinit have enabled the simulation of lattice dynamics under external electric fields that are both time-dependent and spatially inhomogeneous. This extension significantly broadens the range of physical phenomena that can be investigated within the effective Hamiltonian framework, including the response of ferroelectrics and polar materials to realistic field profiles such as pulses, gradients, or locally applied fields.
In this work, I will present the recent implementation of these generalized electric fields in Multibinit, describing the theoretical formulation, the numerical implementation, and illustrative test cases demonstrating the new capabilities.
In addition, I will discuss ongoing and future developments aimed at coupling the lattice degrees of freedom described in Multibinit with the electronic degrees of freedom treated within the Scale-Up electronic framework. This integration is expected to enable simulations where electronic and lattice dynamics are treated consistently, opening the door to electron-phonon physics: excitons, polarons, transport properties, domain wall conductivity...
<br><br>

<hr>
 <a id="Gonze"></a>
### ABINIT project overview and introduction to the workshop
#### Xavier Gonze, UCLouvain, Belgium
I will present an overview of the ABINIT project, including the historical context and evolution, the recently developed capabilities, indicators (bibliometry, files, tests...), description the ABINIT ecosystem, the foreseen evolutions ... Then I will introduce the program of the workshop.
<br><br>

<hr>
 <a id="He"></a>
### TB2J Developments for Spin-Lattice Coupling and Direct ABINIT Workflows
#### He Xu, University of Liège, Belgium
This presentation focuses on two recent developments in TB2J: spin-lattice coupling and a direct interface with ABINIT. For spin-lattice coupling, magnetic exchange parameters are treated as functions of atomic displacements, enabling the calculation of derivatives of exchange paramter J w.r.t. atomic displacement.
  
The approach combines the magnetic-force-theorem Green’s-function formalism used in TB2J with electron-phonon coupling matrices obtained from DFPT, then downfolds these lattice perturbations into a localized Wannier representation. This provides real-space spin-lattice coupling parameters suitable for coupled spin-lattice dynamics and magnon-phonon coupling, with validation demonstrated on SrMnO3.

The second part introduces a direct ABINIT interface for TB2J based on pseudo-atomic orbital projectors from norm-conserving pseudopotentials. Instead of requiring a separate Wannierization step, ABINIT can export the PAO-projected quantities needed by TB2J. The interface constructs projector Green’s functions, includes exchange-correlation and DFT+(U) contributions to onsite spin splitting, and enables magnetic exchange calculations directly from ABINIT planewave results. Together, these developments extend TB2J toward more efficient first-principles workflows for spin-lattice physics and broaden its integration with the ABINIT ecosystem.
<br><br>

<hr>
 <a id="Llorente"></a>
### Magnon-Phonon Dynamics in the van der Waals Magnet CrSBr - A first-principles study
#### Rubén García Llorente, ICMAB-CSIC, Spain<br>Coauthor(s): Miquel Royo, Massimiliano Stengel
Two-dimensional van der Waals magnets are promising platforms for studying coupled magnetic, lattice, and optical phenomena. Among them, CrSBr stands out for its unusual magnetic properties. Recent IR reflectivity measurements reveal a magnetic excitation potentially linked to magnon–phonon coupling [1], though it still lacks theoretical support.

The newly developed TD-DFPT approach for noncollinear spin systems [2], implemented in ABINIT, is ideally suited to address this challenge. We use it to compute the THz linear response of CrSBr in both the lattice and spin sectors. First, we identify the magnon–phonon coupling in the magnetic and dielectric susceptibilities. Then, we reproduce the measured reflectivity to confirm the origin of the resonance. These results showcase the potential of the new implementation while exposing its current limitations, which trace back to underlying ABINIT capabilities.

[1] E. Uykur et al., Phys. Rev. B 111, 174434 (2025).
[2] M. Royo and M. Stengel, Phys. Rev. X 16, 011049 (2026).
<br><br>

<hr>
 <a id="MacEnulty"></a>
### The PseudoDojo web interface: Enhanced accessibility and renovated pseudopotential testing visualization
#### Lórien MacEnulty, UCLouvain, Belgium
The emergence of more precise pseudopotential performance evaluation metrics and their application to the lanthanide series presented Abinit developers with an opportunity to reevaluate the suitability of the PseudoDojo web facilities. We conduct a brief but thorough accessibility and functionality analysis that considers current PseudoDojo usership needs and evaluates compliance with Web Content Accessibility Guidelines (WCAG) 2.2. This analysis revealed the need for moderate extensions of the current user experience (UX), including enhanced compliance with WCAG 2.2, a renovated landing page that aligns with user navigation intuition, and more sophisticated visualization tools for pseudopotential validation testing. On the developers' side, we build a streamlined deployment algorithm designed to render, upon the occasional release of a new pseudopotential table, the PseudoDojo website as a highly automated, static snapshot of the GitHub. Ultimately, we provide suggestions under the guise of cultivating a UX that enriches the PseudoDojo ethos by emphasizing its aptitude as a space for users of all belt ranks to train on and interact with pseudopotentials, not simply the space for training and testing the pseudopotentials themselves.
<br><br>

<hr>
 <a id="Marchese"></a>
### EPIq - A Wannier interpolator willing to interface with ABINIT
#### Guglielmo Marchese, ICMAB-CSIC, Spain
In the last years I have been helping the devoloping of a new package that exploit Wannier interpolation for the accurate calculation of many material properties:
https://the-epiq-team.gitlab.io/epiq-site/
Beside extending its potentialities, we would like to enlarge the number of first principles code EPIq is interfaced with. This developer meeting appeared to me a good chance to present the project and to lay the basis for future collaborations.
<br><br>

<hr>
 <a id="Poncé"></a>
### In search of the electron-phonon contribution to total energy
#### Samuel Poncé, UCLouvain, Belgium<br>Coauthor(s): Xavier Gonze
The total energy is a central quantity in condensed-matter physics, governing structural stability, phase transitions, and polymorphs.   
In standard first-principles approaches, the Born-Oppenheimer (BO) approximation separates electronic and nuclear degrees of freedom, leading to a decomposition of the total energy into electronic and vibrational contributions. 
However, this separation is only approximate, and additional terms may become important when small energy differences are relevant.

In this talk, we revisit the BO framework and derive a formulation of the total energy in the basis of BO electronic wavefunctions. 
Using a perturbative expansion in powers of $M_0^{-1/4}$, where $M_0$ is a characteristic nuclear mass, we identify the hierarchy of contributions beyond the usual electronic and phononic terms.

We show that the first electron-phonon contribution to the total energy appears at fourth order in the mass expansion and can be expressed in terms of quantities closely related to standard electron-phonon matrix elements from density-functional perturbation theory. 
We also clarify the connection with the Allen-Heine-Cardona theory, demonstrating that the sum of zero-point band-energy shifts over occupied states is not itself the electron-phonon contribution to the total energy.

The formalism is implemented in Abinit and applied to cubic diamond and lonsdaleite. 
Although small, the electron-phonon contribution reaches several meV per atom, indicating that it may play a role in systems where subtle energy differences are crucial, such as polymorph stability and precision phase-transition studies.
<br><br>

<hr>
 <a id="Mayorga"></a>
### NOFT, an efficient approach for strongly-correlated systems
#### Mauricio Rodríguez Mayorga, Université de Toulouse, France
In this contribution, we introduce Natural Orbital Functional Theory (NOFT) and summarize the most recent advances in the field. We will discuss efficient implementations of the method, as well as its application to the computation of properties. Finally, we will present our interest in incorporating NOFT into the ABINIT electronic-structure package.
<br><br>

<hr>
 <a id="Romero"></a>
### ABINIT Q&A — LLM & RAG Evaluation: Topic Classification, Prompting Strategies, and Agentic Retrieval
#### Aldo Humberto Romero, West Virginia University, USA<br>Coauthor(s): Gian-Marco Rignanese, Francesco Ricci
The rapid adoption of large language models (LLMs) raises a practical question for domain-specific codes like ABINIT: can these models reliably answer the questions users actually ask, and does Retrieval-Augmented Generation (RAG) improve on native LLM responses?

 We present a systematic evaluation built on 1,174 curated Q&A pairs extracted from the ABINIT mailing-list and Discourse forums, scored by an LLM judge and classified into 18 physics and technical topic categories. Using this dataset as a benchmark, we evaluate two complementary approaches. First, we test eight prompting strategies — from a simple baseline to chain-of-thought reasoning, few-shot examples, and self-consistency — applied to Claude Haiku 4.5 and Sonnet 4.6. The best strategy, a concise professionally-toned instruction, reaches 3.04/5 on a structured factuality rubric. Second, we compare native LLM performance against an Agentic RAG system combining dense embeddings, BM25 hybrid search, and a reranker applied to the ABINIT documentation and Abipy. Modern LLMs (Gemini-3.5-Flash, Sonnet 4.6) reach 4.2/5 — substantially above Agentic RAG at 2.9/5 — primarily because these models have likely encountered the forum content during pre-training. However, when undocumented questions are removed, RAG improves by +0.4 points, confirming that documentation coverage, not retrieval quality, is the primary bottleneck.

We discuss how this evaluation framework can be used practically: to identify documentation gaps, to publish community-maintained prompt templates for ABINIT users, and to use RAG as a fact-checking layer that validates LLM-generated answers against the official manual. The benchmark also provides a versioned test suite to track documentation quality across ABINIT releases.
<br><br>

<hr>
 <a id="Rostami"></a>
### Combined magnetic and structural transition state in first-principles calculations
#### Samare Rostami, UCLouvain, Belgium<br>Coauthor(s): Xavier Gonze
We present a generalized nudged elastic band (NEB) implementation within density-functional theory (DFT) for calculating transition pathways that simultaneously involve atomic, lattice, and magnetic degrees of freedom. Based on a potential-based constrained DFT framework, this method consistently treats magnetic constraints, spin torques, atomic forces, and stresses together with structural variables. While conventional NEB approaches are typically restricted to atomic displacements, our formalism extends the configurational space to include lattice deformations and local magnetic moments, enabling a comprehensive description of coupled structural and magnetic transitions. The implementation supports both fixed-cell and variable-cell NEB approaches across collinear and noncollinear magnetic configurations. Magnetic degrees of freedom are optimized via torque-based dynamics of local moments, while lattice effects are incorporated through generalized cell coordinates derived from the stress tensor. This allows for the simultaneous optimization of atomic positions, cell vectors, and magnetic variables along the minimum-energy path using several implemented schemes, including steepest descent, local L-BFGS, and global BFGS algorithms. To validate the methodology, we present benchmark calculations for representative magneto-structural systems. Specifically, we investigate the bcc-to-hcp transformation in Fe and the ferromagnetic-to-antiferromagnetic transition in FeRh using the variable-cell formalism. Furthermore, we examine spin-reversal processes in two-dimensional $\text{CrI}_3$ to analyze the influence of spin-orbit coupling on transition paths and their associated energy barriers.
<br><br>

<hr>
 <a id="Shu"></a>
### Generalized Bloch Theorem for Spin Spirals in ABINIT
#### Le Shu, UCLouvain, Belgium
Spin spirals are a special case of noncollinear magnetism, where the magnetic moment direction rotates around an axis upon translation in a periodic solid. Spin spiral properties are intriguing. As a particularly exotic emergent property, a ferroelectric polarization can appear in such magnetic state, hence a magnetoelectric coupling is observed.
However, conventional supercell calculations of spin spirals are time consuming. In the absence of spin-orbit coupling (SOC), the generalized Bloch theorem (GBT) allows spin spirals to be treated within the primitive unit cell. 
We describe and validate the GBT framework for spin spirals as implemented in ABINIT, enabling fully self-consistent calculations of total energies, magnetic moments, stresses, forces, and electric polarization. The implementation is validated against supercell calculations, VASP results, and literature data for bulk Fe, $\mathrm{MnF_2}$ and $\mathrm{LiCu_2O_2}$ for total energies and magnetic moments, and against finite-difference and supercell calculations for stresses and forces in BCC Fe. To account for SOC within the GBT framework, we adopt a projected-SOC (PSOC) method retaining only the periodic part of the SOC operator. For the Co/Pt bilayer, this approach reproduces the main features of the full-SOC energy dispersion and agrees excellently with supercell PSOC results. Applied to the multiferroic monolayer $\mathrm{NiBr_2}$, it captures the dominant electronic polarization and reproduces the polarization behavior obtained from supercell PSOC and full-SOC calculations with very good accuracy.
This work provides an efficient first-principles framework for investigating spin spirals and their magnetoelectric response.
<br><br>

<hr>
 <a id="Tantardini"></a>
### Frequency-free dynamical-screening Bethe-Salpeter equation
#### Christian Tantardini, KFUPM, Saudi Arabia
Dynamical screening can substantially renormalize exciton binding energies and oscillator
strengths when characteristic screening modes are not well separated from excitonic energy scales, but retaining the frequency dependence of the screened interaction makes the Bethe--Salpeter equation (BSE) a nonlinear eigenproblem. We present a frequency-free
formulation of the dynamical BSE for periodic solids that keeps the full microscopic
local-field structure of $W_{\mathbf{G}\mathbf{G}'}(\mathbf{q},\omega)$ while representing
its frequency dependence by a systematically refinable multi-pole expansion within a
controlled low-rank screening subspace. Introducing auxiliary amplitudes then yields an
exact linearization into a single structured Hermitian (or pseudo-Hermitian) block
eigenproblem, avoiding frequency scans of $\Omega$ and scaling linearly with the pole rank.
We demonstrate systematic convergence of bound-exciton poles with respect to both the
number of poles and the screening-subspace dimension, and we highlight the resulting
advantages for iterative eigensolvers targeting only a few low-lying excitons.
<br><br>

<hr>
 <a id="Torrent"></a>
### ABINIT on GPU + Spectrum slicing algorithm
#### Marc Torrent, CEA Bruyères-le-Châtel, Université Paris-Saclay, France
This presentation will be divided into two parts.

In the first part, I present the improvements made over the past two years to the ABINIT software as part of its porting to GPU architectures. I will discuss the new features that can take advantage of GPUs, the code modifications that were required, the performance achieved, and the current limitations. Comparisons are shown across different supercomputers, GPU vendors, and physical systems. Ongoing work aimed at improving the code’s portability, such as support for additional compilers and GPU architectures, is also be detailed.

In the second part, I present the implementation of a spectrum slicing filtering algorithm, developed during the postdoctoral work of Ioanna-Maria Lygatsika. We will see that implementing this approach within a plane-wave DFT framework proved challenging. Several modifications and improvements to the algorithm were necessary to make it practical. The algorithm was designed from the outset to run efficiently on hybrid CPU/GPU architectures.

<br><br>

<hr>
 <a id="Tsai"></a>
### Cubic scaling spinor GW in real space and imaginary time
#### Hsiao-Yi Tsai, UCLouvain, Belgium<br>Coauthor(s): Matteo Giantomassi, Xavier Gonze, Samuel Poncé
Many-body perturbation theory, specifically the *GW* approximation, stands as the gold standard for predicting quasi-particle band structures, and band gaps of crystalline materials. However, its application to complex and extended systems is severely hindered by the quartic computational scaling with respect to the system size of conventional implementations. Furthermore, two theoretical challenges still persist: the strong starting-point dependence of the one-shot *GW* approach, and the necessity of fully incorporating non-collinear spin degrees of freedom within many-body perturbation theory. This is particularly important for materials such as perovskites, where spin–orbit coupling (SOC) is intrinsically strong. Even with SOC, Kohn–Sham band structures constitute a poor starting point, markedly underestimating experimental quasiparticle energies thus compromising the accuracy of perturbative approaches. To overcome these limitations, we present the theoretical formalism and implementation of an eigenvalue-only self-consistent (ev*GW*), cubic scaling *GW* method including SOC within the ABINIT code. This is accomplished by evaluating the irreducible polarizability and the *GW* self-energy in the real-space and imaginary-time domains. We study the convergence behavior, assess the numerical stability of the analytic continuation procedure, and present additional techniques to accelerate computation and reduce memory usage. The method is benchmarked against conventional quartic-scaling *GW* approaches for a diverse range of general semiconductors and complex metal-halide perovskites, including Si, GaAs, CsPbI$_3$. We demonstrate that our cubic scaling spinor ev*GW* framework exhibits excellent agreement with conventional methods while delivering a massive computational speedup. This progress opens up the door for the many-body study of larger systems such as defects, interfaces and heterostructures.
<br><br>

<hr>
 <a id="Vasilchenko"></a>
### Variational approach to self-trapped polarons and hopping transport
#### Vasilii Vasilchenko, UCLouvain, Belgium
Polarons are quasiparticles formed in condensed matter when charge carriers couple to the phonons of a system. Present in a wide range of materials with moderate to strong electron–phonon coupling, polaronic effects are responsible for various physical phenomena. These include renormalization of electronic bands, effective mass enhancement, and self-trapping of charge carriers. In the latter process, the charge becomes localized in the potential created by the self-induced polarization. As a result, transport may change from a band-like to the polaron hopping regime, in which transfer occurs through transition events between localization sites.

In this talk, I will discuss how self-trapped polarons and hopping transport can be approached from first principles in ABINIT. In particular, I will focus on the framework of variational polaron equations and its extension for the calculation of minimal energy paths (MEPs) between localization sites. The ability to compute multiple polaronic states and MEPs connecting them on the polaron energy surface provides a way to estimate polaron hopping mobility within Marcus theory. The capabilities of the formalism will be demonstrated using rutile TiO2, a semiconductor that exhibits electron polaron self-trapping and whose conductivity measurements display signatures of polaronic hopping.
<br><br>

<hr>
 <a id="Zabalo"></a>
### Natural optical activity with SOC at transparent frequencies
#### Asier Zabalo, University of Liège, Belgium
We extend the existing longwave DFPT formalism for natural optical activity 
to incorporate spin-orbit coupling effects and to treat finite (transparent) 
frequencies. Using this implementation, we investigate the evolution of the 
static optical rotation of the gyroelectric Pb5Ge3O11 crystal across its 
ferroelectric double-well potential, from the paraelectric P-6 phase to the 
ferroelectric P3 structure, where spin-orbit coupling plays a significant role. 
Our method is further validated by computing the frequency-dependent optical 
rotation of \alpha-quartz, obtaining excellent agreement with experimental 
measurements. As an additional outcome of this work, we have implemented 
in Abinit a new option to compute, within the same SCF cycle, the linear 
response to a magnetic field including both spin and orbital contributions, 
which were previously treated separately. This capability will be useful, e.g., 
for the DFPT calculation of the magnetoelectric tensor including both spin 
and orbital terms.
<br><br>

<hr>
 <a id="Zwanziger"></a>
### NMR Features of ABINIT: Relativistic Terms, Spin Couplings, and Spatial Maps
#### Josef Zwanziger, Dalhousie University, Canada
_No abstract_
<br><br>


# Posters <a id="Posters"></a>

<hr>
 <a id="Béjaud_poster"></a>
### Invar effect in delta plutonium alloys
#### Romuald Béjaud, CEA Bruyères-le-Châtel, Université Paris-Saclay, France
Several long-debated dynamical and elastic anomalies of δ-Pu and its alloys (Pu-Al/Ga/In) have been captured within an unprecedented unified theoretical framework. This achievement is made possible by machine learning-accelerated ab initio simulations, which enable a detailed description of strong electronic correlations and explicit temperature effects.
For pure δ-Pu, the present simulations—within this unified framework—successfully reproduce the experimental observations of negative thermal expansion, equilibrium volume, and anomalous softening of elastic properties. Our analysis demonstrates that the distinctive behavior of δ-Pu is almost entirely attributable to large anharmonic effects, which are linked to the extreme softening of the phonon spectrum.
This simulation approach has recently been extended to Pu-Al/Ga/In alloys. The results reveal significant anharmonic effects upon the addition of δ-stabilizing elements and reproduce the well-known invar effect in δ-Pu alloys, where thermal expansion transitions from negative to positive as a function of Al/Ga/In content. These results are a step forward toward a better understanding of alloying effects in plutonium.
<br><br>

<hr>
 <a id="Bruneval_poster"></a>
### Comparison of Plane-Wave and Gaussian Basis Sets for Correlated Wavefunction-based Methods in Solids
#### Fabien Bruneval, CEA Saclay, Université Paris-Saclay, France
_No abstract_
<br><br>

<hr>
 <a id="Chen_poster"></a>
### Electron-phonon coupling using GW perturbation theory for semiconductors and insulators
#### Siyu Chen, UCLouvain, Belgium 
Electron–phonon interactions induce renormalizations of quasiparticle energies in semiconductors and insulators, yet their consistent treatment at the GW level remains challenging. We present the implementation of GW perturbation theory within the ABINIT package to compute GW–level electron–phonon coupling matrix elements from the first–order variation of the GW self–energy with respect to phonon perturbations. The approach is built on Phys. Rev. Lett. 122, 186402 (2019) and combines Sternheimer with a Coulomb-hole static remainder to reduce the computational cost which enables direct calculations of zero–point renormalization at the GW level without resorting to Wannier interpolation. We apply the method to two prototypical wide-gap materials, diamond and GaP, and analyze the resulting zero–point renormalization, highlighting both the consistency achieved for GW–level couplings and the sensitivity of derived quantities to current approximations. 
<br><br>

<hr>
 <a id="Fauser_poster"></a>
### Excited electronic states calculation in the GW approximation coupled to the Projector Augmented-Wave approach
#### Steffen Fauser, CEA Bruyères-le-Châtel, Université Paris-Saclay, France
The GW approximation describes the electronic self-energy through the product of the
single-particle Green’s function (G) and the screened Coulomb interaction (W). It enables
to compute quasiparticle correction to the DFT energies, in order to calculate accurate
band structures and excitation properties.
The Projector augmented-wave (PAW) approach [1] combines the efficiency of pseudopo-
tentials with the accuracy of all-electron methods. It relates the pseudo wavefunction to
the all-electron wavefunction through a linear transformation that restores the all-electron
properties.
The combination of the GW and PAW approaches is a conceptually and numerically
challenging task. In the past, several attempts to this problem have been discussed [2,3,4].
In this work, we reexamine this issue in great detail, in particular the different possible
choices in the computation of the oscillator strength matrix elements, the treatment of the
exchange self-energy, the completeness of the various basis sets involved, the limit in the
sum over high energy bands in the correlation self-energy, the potential occurrence of cross
terms between the plane wave and onsite basis sets, and the different implementations in
the ABINIT and VASP electronic structure codes.

1. P. Blochl, Phys. Rev. B 1994, 50 (24), 17953
2. B. Arnaud, M. Alouani, Phys. Rev. B 2000, 62 (7), 4464
3. M. Shishkin, G. Kresse, Phys. Rev. B 2006, 74 (3), 035101
4. J. Klimes, M. Kaltak, G. Kresse, Phys. Rev. B 2014, 90 (7), 075125
<br><br>

<hr>
 <a id="Gendron_poster"></a>
### DMFT in ABINIT: Recent advances and applications
#### Frédéric Gendron, CEA Bruyères-le-Châtel, Université Paris-Saclay, France<br>Coauthor(s): Bernard Amadon
The rationalization of magnetic properties of metallic plutonium is still subject to debate nowadays from an ab-initio perspective. Elemental plutonium contains a partially filled 5f shell that should lead to strong electron correlation effects, and therefore, to a sizable local magnetic moment. However, experimentally no evidence of ordered nor disordered local
moments has been characterized in metallic plutonium. Indeed, alloyed δ-Pu exhibits a nearly temperature-independent magnetism at low temperatures that is characteristic of a non magnetic ground state. In this presentation, we will discuss the calculated magnetic susceptibilities obtained using the combination of density functional theory and dynamical mean field theory (DFT+DMFT). Consistent with experimental data, the ground state at low temperature is found to be nonmagnetic and characterized as a mixed-valence system, where the local magnetic moment is screened by the conduction electrons. As the temperature rises a local magnetic moment emerges with antiparallel orbital and spin angular momenta, leading to a transition from Pauli-like behavior to an apparent weak Curie-Weiss magnetism in the uniform and local susceptibilities.
<br><br>

<hr>
 <a id="Lebrun_poster"></a>
### Electron-phonon coupling in the Two-Temperature Model
#### Harmonie Lebrun, CEA Saclay, Université Paris-Saclay, France<br>Coauthor(s): James Boust, Fabien Brieuc, Marc Torrent
Laser-matter interactions are a rising concern in pump-probe experiments involving short-pulsed lasers in the femtosecond range. When irradiated, the lattice system is untouched conversly to the electrons which absorb most of the energy. The Two-Temperature Model (TTM) often used in simulation describes the exchange of energy between electrons and the lattice with the help of a coupling factor.

This poster will present the basis of the TTM and some hypothesis leading to its derivation. Limitation to this model are briefly discussed.
<br><br>

<hr>
 <a id="Paradis_poster"></a>
### Exploration of anharmonic phonons and their effects in metal hydrides
#### Félix Paradis, Université du Québec à Trois-Rivières, Canada
_No abstract_
<br><br>

<hr>
 <a id="Priol_poster"></a>
### Acceleration of electronic density calculation with machine learning
#### Adrien Le Priol, CEA Bruyères-le-Châtel, Université Paris-Saclay, France
Accelerating DFT calculations is a major challenge for simulating large atomic systems. While recent machine learning models accurately predict electron density, their massive computational cost during inference often negates the time saved by using a good density guess to initiate SCF cycles. Dimensionality reduction is therefore crucial to compress the density representation (in real or reciprocal space).

This poster presents the roadmap of my PhD project, focusing on a machine learning strategy for density prediction based on atomic positions.
<br><br>

<hr>
 <a id="Rostami_poster"></a>
### Anisotropic temperature-dependent lattice parameters and elastic constants from ﬁrst principles
#### Samare Rostami, UCLouvain, Belgium<br>Coauthor(s): Matteo Giantomassi , Xavier Gonze
We present an efﬁcient implementation of the Zero Static Internal Stress Approximation (ZSISA) within the Quasi-Harmonic Approximation framework to compute anisotropic thermal expansion and elastic constants from ﬁrst principles. By replacing the costly multidimensional minimization with a gradient-based method that leverages second-order derivatives of the vibrational free energy, the number of required phonon band structure calculations is signiﬁcantly reduced: only six are needed for hexagonal, trigonal, and tetragonal systems, and 10–28 for lower-symmetry systems to determine the
temperature dependence of lattice parameters and thermal expansion. This approach enables accurate modeling of anisotropic thermal expansion while substantially lowering computational cost compared to standard ZSISA method. The implementation is validated on a range of materials with symmetries from cubic to triclinic and is extended to compute temperature-dependent elastic constants with only a few additional phonon band structure calculations.
<br><br>
