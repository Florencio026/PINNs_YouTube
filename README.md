# Comprehensive Poschl-Teller Analysis: Analytic, Harmonic Oscillator Basis, and PINN Solutions

This repository contains a complete and well-documented workflow for solving the one-dimensional Poschl-Teller quantum well using three complementary approaches:

1. **Analytic Solutions**  
   The code computes and visualizes the exact energy eigenvalues and normalized eigenfunctions for the Poschl-Teller potential. It also verifies orthonormality and the diagonal form of the Hamiltonian in the analytic basis.

2. **Harmonic Oscillator Basis Expansion**  
   The Poschl-Teller Hamiltonian is expanded in the basis of harmonic oscillator eigenfunctions. The code checks orthonormality, diagonalizes the Hamiltonian, and compares the numerical eigenstates with analytic results.

3. **Physics-Informed Neural Network (PINN) Solution**  
   A PINN is set up and trained to solve the ground state of the Poschl-Teller well, using both physics and data losses. The results are compared directly to the analytic solution.

The notebook is designed for a clear, step-by-step walkthrough and is suitable for both educational and research purposes.  
All integration is performed using Simpson's rule (with appropriate cutoffs for speed and accuracy).

## Usage

- Clone this repository
- Open the notebook in Google Colab or Jupyter
- Run each cell in sequence to reproduce the results and plots

## Requirements

- Python >= 3.8
- numpy
- matplotlib
- pandas
- scipy
- torch

You can install dependencies with:

```bash
pip install numpy matplotlib pandas scipy torch
```

## MIT License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

If you use or adapt this code, please cite or link back to this repository and the video.
