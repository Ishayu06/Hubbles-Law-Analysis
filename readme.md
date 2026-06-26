# 🌌 Recreating Hubble's Law using Type Ia Supernovae

A computational cosmology project that reconstructs **Hubble's Law** using observational **Type Ia Supernova** data from the **Pantheon+SH0ES** compilation.

This project demonstrates how modern cosmological observations can be used to estimate the **Hubble Constant (H₀)** through numerical fitting and scientific visualization in Python.



## Project Overview

Edwin Hubble's discovery that galaxies recede from us at velocities proportional to their distances provided the first observational evidence that the Universe is expanding.

Today, this relationship is measured using **Type Ia Supernovae**, which act as standard candles for determining cosmological distances. This project reproduces that analysis by fitting observational data from the Pantheon+SH0ES dataset to estimate the Hubble Constant.



## Objectives

* Load and preprocess observational supernova data
* Construct the Hubble Diagram
* Estimate the Hubble Constant (H₀)
* Visualize the best-fit cosmological model
* Demonstrate numerical data analysis techniques used in observational cosmology



## Dataset

**Pantheon+SH0ES Type Ia Supernova Compilation**

The Pantheon+SH0ES dataset is one of the largest publicly available collections of Type Ia Supernova observations and is widely used in modern observational cosmology.

Location:

```text
data/Pantheon+SHOES.dat
```



## Methodology

The notebook performs the following workflow:

1. Load the Pantheon+SH0ES dataset.
2. Clean and preprocess the observational data.
3. Compute the required cosmological quantities.
4. Fit the observational data using SciPy.
5. Estimate the Hubble Constant.
6. Generate the Hubble Diagram.



## Results

### Estimated Hubble Constant

**H₀ = 69.52 ± 0.19 km s⁻¹ Mpc⁻¹**

The estimated value is consistent with modern observational measurements within the assumptions of the implemented cosmological model.



## Repository Structure

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
├── .gitignore
└── requirements.txt
```



## Technologies Used

* Python
* NumPy
* Pandas
* SciPy
* Matplotlib
* Jupyter Notebook



## Running the Project

1. Clone the repository.

```bash
git clone https://github.com/Ishayu06/Hubbles-Law-Analysis.git
```

2. Install the required Python libraries.

```bash
pip install numpy pandas matplotlib scipy jupyter
```

3. Open the notebook.

```bash
jupyter notebook
```

4. Run every cell in:

```text
notebooks/Hubbles\_Law\_Analysis.ipynb
```



## Future Improvements

* χ² goodness-of-fit analysis
* Residual analysis
* Confidence interval estimation
* Interactive visualizations
* Comparison with alternative cosmological models



## Author

**Ishayu Basu**

Electronics \& Instrumentation Engineering
VIT Vellore

Interested in Computational Astrophysics, Cosmology and Modified Gravity.





