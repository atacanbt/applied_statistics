
# HDip Data Analytics — Applied Statistics

This repository provides solutions to the lecturer's [Applied Statistics assessment problems](https://github.com/ianmcloughlin/applied-statistics/blob/main/assessment/problems.md).
It demonstrates simulation-based statistical reasoning, hypothesis testing, and clear communication of results using Jupyter notebooks.



## Quick Start

1. **Clone the repository:**
	 ```bash
	 git clone https://github.com/atacanbt/applied_statistics.git
	 cd applied_statistics
	 ```

2. **Set up Python environment:**
	 - With `venv` (recommended):
		 ```bash
		 python -m venv .venv
		 source .venv/bin/activate
		 pip install --upgrade pip
		 ```
	 - Or with `Conda`:
		 ```bash
		 conda create --name statsenv python=3.10
		 conda activate statsenv
		 ```

3. **Install dependencies:**
	 ```bash
	 pip install -r requirements.txt
	 # If needed:
	 pip install jupyter ipykernel
	 ```

4. **Run the notebooks:**
	 - In VS Code: Open any `.ipynb` file and select your environment.
	 - With Jupyter:
		 ```bash
		 python -m ipykernel install --user --name=applied-stats-env --display-name "Python (applied-stats-env)"
		 jupyter notebook
		 ```
	 - Or launch in Google Colab:
<a target="_blank" href="https://colab.research.google.com/github/atacanbt/applied_statistics/blob/main/problems.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>



## Repository Structure

```
.
├── problems.ipynb      # Solutions to assessment problems
├── requirements.txt    # Python dependencies
└── README.md           # Project overview
```



## Style and Conventions

- Notebooks are structured as narratives, combining code, results, and interpretation.
- Code cells are kept short and focused, with explanations provided in markdown.
- Visualizations use `Matplotlib` and `Seaborn` and are clearly labelled.



## References
References are cited within `problems.ipynb` where used.



## Acknowledgments

- Assessment problems and guidance provided by the module [lecturer](https://github.com/ianmcloughlin/applied-statistics).


## Contact

Atacan Buyuktalas — atacanbuyuktalas@gmail.com
