# HDip Data Analytics — Applied Statistics

This repository contains detailed solutions to problems outlined in the lecturer's
[Applied Statistics assessment problems notebook](https://github.com/ianmcloughlin/applied-statistics/blob/main/assessment/problems.md).



## Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/atacanbt/applied_statistics.git
cd applied_statistics
```

### 2. Set up Python environment

You can use either a virtual environment (venv) or Conda:

**Option A: venv (recommended for most users)**
```bash
python -m venv .venv
source .venv/bin/activate  # zsh/bash
pip install --upgrade pip
```

**Option B: Conda**
```bash
conda create --name statsenv python=3.10
conda activate statsenv
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
# If you plan to run notebooks and Jupyter isn't installed:
pip install jupyter ipykernel
```

### 4. Run the notebooks

- **In VS Code:** Open any `.ipynb` file and select the correct Python environment (either `.venv` or `statsenv`).
- **With Jupyter:**
	```bash
	# If using venv or conda, activate your environment first
	python -m ipykernel install --user --name=applied-stats-env --display-name "Python (applied-stats-env)"
	jupyter notebook  # or: jupyter lab
	```
- **Google Colab**
Alternatively, you can run the notebook on web page through Google Colab by clicking on the badge below.

*(badge will be here)

You're now ready to explore and run the solutions!


## Repository structure

```
.
├── problems.ipynb                # Worked solutions to assessment problems
├── requirements.txt              # Python dependencies
└── README.md                     # This file
```

Notes:
- Solutions are primarily in `problems.ipynb`.


## How to run the notebooks

- Preferred: open in VS Code, ensure the Python interpreter points to `.venv`, and run cells.
- Alternative: launch Jupyter from the environment:

```bash
source .venv/bin/activate
# If Jupyter isn't installed yet:
# pip install jupyter ipykernel
python -m ipykernel install --user --name=applied-stats-venv --display-name "Python (.venv)"
jupyter notebook  # or: jupyter lab
```

## Style and conventions

- Code is written for readability with explanatory markdown in notebooks.
- Plots are generated with Matplotlib and Seaborn, and labeled for publication-quality output.


## References
All references are cited directly within `problems.ipynb` at the point where they are used or mentioned.


## Acknowledgments

- Assessment and notebook prompts by the lecturer: https://github.com/ianmcloughlin/applied-statistics

## Contact

Atacan Buyuktalas - atacanbuyuktalas@gmail.com
