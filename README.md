# Ising Model in Different Topologies

This project contains implementations of the **Ising Model** in various network topologies, with Monte Carlo simulations and thermodynamic property analysis.

## 📄 Publications

- **English Version**: See `Ising_English_Version` for the article in English
- **Spanish Version**: See `Articulo.pdf` for the article in Spanish

## 📋 Description

The Ising Model is a mathematical model of ferromagnetism in statistical mechanics. This repository includes simulations in the following topologies:

- **Linear (1D)**: One-dimensional chain
- **Square (2D)**: Two-dimensional square lattice
- **Cubic (3D)**: Three-dimensional cubic lattice
- **Honeycomb (2D)**: Hexagonal lattice (honeycomb)

## 🔬 Features

- Monte Carlo simulations with Metropolis algorithm
- Phase transition analysis
- Calculation of thermodynamic properties (energy, magnetization, specific heat, susceptibility)
- System configuration visualizations
- Optimization with Numba for fast computations

## 📁 Project Structure

```
Ising_Model/
├── notebooks/
│   ├── ising_lineal.ipynb      # Linear lattice simulation
│   ├── ising_cuadrada.ipynb    # Square lattice simulation
│   ├── ising_cubica.ipynb      # Cubic lattice simulation
│   └── ising_honeycomb.ipynb   # Honeycomb lattice simulation
├── requirements.txt            # Project dependencies
├── LICENSE                     # Project license
└── README.md                   # This file
```

## 🚀 Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package manager)

### Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/your-username/Ising_Model.git
cd Ising_Model
```

2. (Optional) Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Linux/Mac
# or
venv\Scripts\activate     # On Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## 💻 Usage

### Running the notebooks

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Navigate to the `notebooks/` folder and open the notebook you want to explore.

3. Run the cells sequentially to see the simulations and results.

### Available Notebooks

#### 🔗 ising_lineal.ipynb
Ising Model simulation on a one-dimensional chain. Includes:
- Diluted system with occupation probability
- Magnetization vs temperature analysis
- Study of phase transitions in 1D

#### ⬜ ising_cuadrada.ipynb
Ising Model simulation on a 2D square lattice. Includes:
- Metropolis algorithm for system evolution
- Spin configuration visualization
- Critical temperature calculation
- Thermodynamic property analysis

#### 🧊 ising_cubica.ipynb
Ising Model simulation on a 3D cubic lattice. Includes:
- 3D implementation of Monte Carlo algorithm
- Analysis of critical phenomena in 3D
- Statistical property visualization

#### 🔶 ising_honeycomb.ipynb
Ising Model simulation on a hexagonal (honeycomb) lattice. Includes:
- Honeycomb topology construction
- Different coordination analysis (z=3)
- Comparison with other topologies

## 📊 Calculated Properties

The notebooks calculate the following thermodynamic properties:

- **Energy**: Total system energy
- **Magnetization**: Average magnetic moment
- **Specific Heat**: Heat capacity of the system
- **Magnetic Susceptibility**: System response to magnetic fields
- **Correlations**: Spatial correlation functions

## 🔧 Technologies Used

- **NumPy**: Numerical computations and arrays
- **Matplotlib**: Data visualization
- **Numba**: JIT compilation for performance optimization
- **Jupyter**: Interactive notebooks

## 📖 References

- Ising, E. (1925). "Beitrag zur Theorie des Ferromagnetismus"
- Metropolis, N. et al. (1953). "Equation of State Calculations by Fast Computing Machines"
- Onsager, L. (1944). "Crystal Statistics. I. A Two-Dimensional Model with an Order-Disorder Transition"

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 🤝 Contributions

Contributions are welcome. Please:

1. Fork the project
2. Create a branch for your feature (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## 👤 Author

Your Name - [@your-username](https://github.com/your-username)

## ⭐ Acknowledgments

- To the statistical physics and computational mechanics community
- To the developers of NumPy, Matplotlib, and Numba for their excellent tools

---

**Note**: This project is for educational and research purposes in statistical physics.
