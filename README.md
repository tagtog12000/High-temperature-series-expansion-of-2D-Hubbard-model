We investigated the two-dimensional Hubbard model using many-body perturbation theory, focusing on the systematic computation of thermodynamic properties. The contributions of generalized Hugenholtz (Feynman) diagrams were evaluated symbolically and reformulated using divided differences, enabling efficient and precise calculations. We derived the coefficients of the grand potential expansion up to the eighth order in both the interaction potential (\( U \)-expansion) and the inverse temperature (\( \beta \)-expansion).

The provided code can generate the high-temperature coefficients of the grand potential (free energy) up to any desired order in \(\beta\) (the inverse of temperature, \(\beta = \frac{1}{k_B T}\), where \(k_B\) is the Boltzmann constant), but is limited to order 7 in the expansion in terms of \(U\). Higher-order terms beyond 7 in many-body perturbation theory (MBPT) are also available; however, due to the large size of the data (approximately 10 GB for the eighth order), we are unable to upload them to the GitHub repository. These data can be provided upon reasonable request.

How to run the code:
1. Copy all files in the same directory.
2. Open the Mathematica file "High temperature series expansion of 2D Hubbard model.nb".
3. Execute the code by pressing "Shift+Enter".
