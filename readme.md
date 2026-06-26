\# 🌌 Recreating Hubble's Law using Type Ia Supernovae



A Python-based cosmological data analysis project that reconstructs \*\*Hubble's Law\*\* using the \*\*Pantheon+SH0ES Type Ia Supernova dataset\*\*. The objective of this project is to estimate the \*\*Hubble Constant (H₀)\*\* through observational data analysis and visualize the expansion of the Universe.



\---



\## Project Overview



Hubble's Law describes the linear relationship between the recession velocity of galaxies and their distance from Earth. Modern cosmology estimates this relationship using observations of \*\*Type Ia Supernovae\*\*, which serve as standard candles for measuring cosmological distances.



This notebook reproduces this analysis by loading observational supernova data, performing numerical fitting, and estimating the value of the Hubble constant.



\---



\## Dataset



\*\*Pantheon+SH0ES\*\*



The Pantheon+SH0ES compilation is one of the largest publicly available collections of Type Ia Supernova observations and is widely used in observational cosmology.



\---



\## Methodology



The analysis consists of:



\* Loading and preprocessing the Pantheon+SH0ES dataset

\* Computing cosmological quantities required for fitting

\* Performing numerical curve fitting using SciPy

\* Constructing the Hubble Diagram

\* Estimating the Hubble Constant (H₀)

\* Visualizing the best-fit model



\---



\## Results



\*\*Estimated Hubble Constant\*\*



\[

H\_0 = 69.52 \\pm 0.19\\ \\text{km s}^{-1}\\text{Mpc}^{-1}

]



The obtained value is consistent with modern observational estimates within the assumptions of the implemented cosmological model.



\---



\## Repository Structure



```text

Hubbles-Law-Analysis

│

├── data/

│   └── Pantheon+SHOES.dat

│

├── notebooks/

│   └── Hubbles\_Law\_Analysis.ipynb

│

├── figures/

│

├── README.md

├── requirements.txt

└── .gitignore

```



\---



\## Technologies Used



\* Python

\* NumPy

\* Pandas

\* SciPy

\* Matplotlib

\* Jupyter Notebook



\---



\## Future Improvements



\* Residual analysis

\* χ² goodness-of-fit estimation

\* Uncertainty propagation

\* Comparison with ΛCDM cosmological models

\* Additional visualization of cosmological parameters



\---



\## Author



\*\*Ishayu Basu\*\*



Electronics \& Instrumentation Engineering

VIT Vellore



Interested in Computational Astrophysics, Cosmology and Modified Gravity.




