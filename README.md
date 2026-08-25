# Luis F. Martinez-Gomez

PhD computational materials scientist (Emory University, 2026). I model surfaces and interfaces from first principles — and I build and maintain the codes that do it.

**Contact** · lfmartg@outlook.com · [LinkedIn](https://www.linkedin.com/in/luis-martinez-gomez-759888371/) · Austin, TX

## What I work on

**Surfaces and adsorption from DFT.** Slab models in VASP with self-consistent noncollinear spin-orbit coupling, adsorption free energies benchmarked against hydrogen-evolution activity descriptors, and bonding decomposition with pCOHP.

**Machine-learned interatomic potentials.** Zero-shot MACE-MP-0 benchmarking on NbP-H with reference-invariant energy curves, force-resolved validation, calculation provenance, and reproducible CPU inference. The benchmark captures the overall energy trend (Pearson r = 0.9445) while exposing a 0.8057 eV/Å H vertical-force MAE that aggregate force metrics obscure.

**From DFT to a model you can reason about.** Maximally localized Wannier functions with disentanglement, tight-binding Hamiltonians validated back against the DFT bands, surface projected spectral functions, and kernel-polynomial methods.

**Topological matter meeting chemistry.** Weyl semimetals, Fermi arcs, Su-Schrieffer-Heeger chains — and what their surface states do to a chemisorbed molecule.

**Theory against experiment.** Vibronic Fano-resonance models reconciled with transient-IR spectra of catalyst-functionalized quantum dots, with the Lian group at Emory and the Kubiak group at UC San Diego.

## Repositories

| Repository | What it is |
| --- | --- |
| [nbp-mace](https://github.com/lfmart2/nbp-mace) | Reproducible zero-shot MACE-MP-0 benchmark for H on NbP: DFT-relative energy curves, H-resolved force errors, provenance, tests and measured CPU timing |
| [Electronic_Structure](https://github.com/lfmart2/Electronic_Structure) | End-to-end VASP and Quantum ESPRESSO workflows: relaxation, SCF/NSCF, bands and DOS, Wannier90 — across SOC and non-SOC regimes |
| [Quantum_Dots](https://github.com/lfmart2/Quantum_Dots) | Julia. Electronic wavefunctions and adsorbate-quantum-dot electronic couplings; Fano lineshapes for infrared spectra |
| [Codes](https://github.com/lfmart2/Codes) | Tight-binding, kernel-polynomial and post-processing utilities in Python, Julia, MATLAB and Mathematica |
| [Tutorials](https://github.com/lfmart2/Tutorials) | Teaching material, from programming fundamentals through theory |

## Beyond the simulations

I built and maintained my group's **VASP, Quantum ESPRESSO and Wannier90 installations from source** — Intel and GNU toolchains, Open MPI, Intel MKL with ScaLAPACK and BLACS, FFTW, the VASP-Wannier90 interface, and a GPU build I validated myself.

Before the PhD I was a nanotechnology undergraduate at UNAM, where I ran a **JEOL JIB-4500 SEM-FIB** (secondary-electron and backscattered imaging, gallium-ion milling and beam-induced deposition) and **TEM** with bright field, dark field, Z-contrast and selected-area electron diffraction.

## Publications

**J. Phys. Chem. Lett. 17, 1760 (2026)** — **Martinez-Gomez, L.**; Ribeiro, R. F. [Topological advantage for adsorbate chemisorption on conjugated chains](https://pubs.acs.org/jpclcd/article/17/6/1760/5088918/Topological-Advantage-for-Adsorbate-Chemisorption)

**arXiv:2606.16994 (2026), under review** — **Martinez-Gomez, L.**; Ribeiro, R. F. [Hydrogen chemisorption and current-induced spin polarization on NbP](https://arxiv.org/abs/2606.16994)

**arXiv:2410.11793 (2024), under review** — **Martinez-Gomez, L.**; Gebre, S. T.; Lian, T.; Ribeiro, R. F. [Theory of vibronic adsorbate-surface Fano resonances](https://arxiv.org/abs/2410.11793)

**J. Am. Chem. Soc. 147, 10966 (2025)** — Gebre, S. T.; Miller, C. R.; **Martinez-Gomez, L.**; Kubiak, C. P.; Ribeiro, R. F.; Lian, T. [Fano resonance in CO2 reduction catalyst functionalized quantum dots](https://pubs.acs.org/doi/10.1021/jacs.4c14499)

**J. Chem. Phys. 163, 084713 (2025)** — Gebre, S. T.; **Martinez-Gomez, L.**; He, S.; Yang, Z.; Cattaneo, M.; Ribeiro, R. F.; Lian, T. [Shell-thickness dependent Fano resonance in molecular catalyst functionalized CdSe/ZnS core/shell QDs](https://pubs.aip.org/aip/jcp/article-abstract/163/8/084713/3360440)
