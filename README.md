# High-Fidelity Grafting Energy Prediction

This project provides a computational framework for predicting grafting energy barriers on amorphous 2D lattices using machine learning and physical modeling. The workflow includes lattice generation, site identification, energy calculations, and the application of metric learning and kernel regression to predict and analyze grafting barriers.

## Features

- **Lattice Generation:** Create amorphous 2D lattices with tunable disorder and site fractions.
- **Site Identification:** Locate graftable and competing sites on the lattice.
- **Energy Calculations:** Compute grafting and adsorption energies using Morse potentials.
- **Machine Learning:** 
  - Metric learning (MLKR) and kernel regression for barrier prediction.
  - Model evaluation with KNeighborsRegressor and KernelRidge.
  - Active learning and error analysis.
- **Visualization:** 
  - Histograms, KDEs, and rug plots for energy distributions.
  - Residual analysis and population evolution plots.

## File Structure

- `Grafting_compact.ipynb`: Main notebook for data generation, model training, and analysis.
- `il_pedagogical.py`: Pedagogical implementation of energy calculations and histogram functions.
- `il.py`: Core machine learning and metric learning routines.
- `lattice.py`: Lattice generation and manipulation utilities.
- `potentials.py`: Morse potential and related energy functions.
- `visualization.py`: Plotting and visualization helpers.
- `README.md`: Project documentation.
- `UGP_research paper.pdf`: Reference research paper.
- `desktop.ini`: System file.

## Getting Started

### Prerequisites

- Python 3.7+
- Required packages: `numpy`, `matplotlib`, `seaborn`, `scipy`, `scikit-learn`, `metric-learn`

Install dependencies:
```sh
pip install numpy matplotlib seaborn scipy scikit-learn metric-learn
```

### Usage

1. **Run the Notebook:**  
	Open `Grafting_compact.ipynb` in Jupyter or VS Code and execute cells sequentially.
2. **Modify Parameters:**  
	Adjust lattice size, temperature, and fractions at the top of the notebook as needed.
3. **Explore Results:**  
	Visualizations and model outputs will be generated in the notebook.

### Scripts

- For standalone calculations or batch runs, use functions in `il_pedagogical.py`.

## Citation

If you use this code, please cite the associated research paper:  
`UGP_research paper.pdf`

## License

This project is for academic use. See the research paper for details.

---

*For questions or contributions, please open an issue or pull request.*
