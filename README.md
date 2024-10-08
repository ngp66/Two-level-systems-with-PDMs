# Two-level-systems-with-PDMs

This project explores the evolution of two level systems (TLS) with permanent dipole moments (PDM) in electric fields enhanced by spherical nanoparticles with the aim to achieve a coherent response. To do that, the field decay rates and enhancement by spherical nanoparticles are calculated by following the Mie scattering formalism. The evolution of the TLS populations for systems positioned near the hotspots of the nanosphere is determined by using the Lindblad Master equation and a coherent response is found for parameters where the Rabi frequency becomes nearly constant for certain position ranges.

The code calculates and visualises the field enhancement by spherical nanoparticles of arbitrary sizes and the Rabi frequency of two-level-systems with PDMs positioned in the vicinity of the nanoparticle:

  <img src="https://github.com/user-attachments/assets/187d6f96-ed11-40df-8c27-d73929264e04" alt="field enhancement" width="400"/>       <img src="https://github.com/user-attachments/assets/0c4d1edb-52a6-4735-a9c7-f55b7ffd27ca" alt="rabi frequency" width="350"/>
  
When arrays of TLS are positioned near the peak of the Rabi frequency vs distance plot, they can sustain coherence over the order of 0.01 ns. This allows for a coherent response even when the TLS to be separated by a nanometer, lifting some of the required experimental precision for such systems. 

<img src="https://github.com/user-attachments/assets/75bb6162-2577-487d-ba42-8b280b7a246b" alt="evolution with PDM" width="800"/>

### Important references
#### Refractive index data:

[[1]](https://pubs.acs.org/doi/10.1021/ph5004237) McPeak KM, Jayanti SV, Kress SJP, Meyer S, Iotti S, Rossinelli A, et al. Plasmonic films can easily be better: Rules and recipes. ACS Photonics 2. 2015:326-33

#### Mie scattering derivations:

[[2]](https://api.semanticscholar.org/CorpusID:124119456) Thovsen KB. Evaluation of Mie scatter approximation formulas for the scattering of infrared light at biological cells; 2013

[[3]](https://www.sciencedirect.com/science/article/pii/0039602888907765) Kim YS, Leung PT, George TF. Classical decay rates for molecules in the presence of a spherical surface: A complete treatment. Surface Science. 1988;195(1):1-14

#### Decay rate derivations:

[[3]](https://www.sciencedirect.com/science/article/pii/0039602888907765) above and

[[4]](https://link.aps.org/doi/10.1103/PhysRevB.76.115123) Mertens H, Koenderink AF, Polman A. Plasmon-enhanced luminescence near noble-metal nanospheres: Comparison of exact theory and an improved Gersten and Nitzan model. Phys Rev B. 2007;76:115123
