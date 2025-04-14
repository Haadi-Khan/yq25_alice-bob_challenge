# From Noise to Information: Reconstructing Quantum States from Wigner Functions

<div align="center">
<b>Yale Quantum Institute 2nd Place Grand Prize @ YQuantum 2025.</b>
</div>

Team Alice & Bobs ([Haadi Khan](https://github.com/Haadi-Khan), [Arul Rhik Mazumder](https://github.com/arulrhikm), [Tanmay Neema](https://github.com/tanmay3663), [Alice Wang](https://github.com/atxwang), [Ryan O'Farrell](https://github.com/ro-farrell))

<div align="center">
  <img src="images/anb_logo.png" alt="Cat" width="150" />
</div>
<div align="center">
<strong>YQuantum 2025 - Alice &amp; Bob YQuantum Challenge</strong>
</div>

## Overview

For quantum computing, the [Wigner function](https://en.wikipedia.org/wiki/Wigner_quasiprobability_distribution) is a natural way to measure quantum states. It provides a clear view of the state, making it ideal for state tomography ([quantum tomography](https://en.wikipedia.org/wiki/Quantum_tomography))—the method we use to see what’s happening inside a quantum computer.

<div align="center">
  <img src="images/cat.gif" alt="Cat" width="300" />
</div>


In practice, turning these measurements into a complete picture of the state is challenging due to noise and missing data. This challenge focuses on overcoming these issues to improve state reconstruction.

The Wigner function is frequently used to characterize quantum states because of its close relationship to measurable quantities and its direct connection to the [density matrix](https://en.wikipedia.org/wiki/Density_matrix) $\rho$. Indeed, the Wigner function can be seen simply as an alternative representation of the quantum state, with a one-to-one correspondence between it and the density matrix—meaning both contain exactly the same information.

In practice, reconstructing a density matrix from experimental Wigner measurements involves noise, missing data points, and the need for sophisticated numerical routines.

The central aims of this challenge are:

1. To implement Wigner-based quantum state reconstruction (tomography).
2. To investigate and mitigate diverse noise sources.
3. To explore self-supervised machine learning strategies for denoising.

You will:

- Generate Wigner functions of various quantum states (e.g., Gaussian states, Fock states, cat states).
- Develop a “fit” function that reconstructs $\rho$ from Wigner data.
- Fit real experimental Wigner functions.
- Deal with Gaussian noise and affine distortions in synthesized data.

What you'll learn in this challenge:

- Explore the fundamentals of linear algebra and probability/statistics.
- Gain insights into quantum states, density matrices $\rho$, fidelity measures, quantum tomography, and phase space representations.
- Develop your Python skills through hands-on quantum system simulations and optimization.

We recommend reviewing the **Theory Background Tutorial** to ensure a strong foundation in the concepts presented in this challenge, whether you're new to them or already familiar.

<center><strong>Good luck! 😺</strong></center>

