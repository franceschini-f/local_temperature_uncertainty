# Local Temperature Uncertainty Indices

This repository accompanies the Technical Report "Local Indices of Physical Climate Uncertainty" by Giuseppe Cavaliere, Luca Fanelli and Fabio Franceschini. It contains the R scripts needed to form the indexes of local temperature uncertainty therein studied. These indices are designed to measure temperature uncertainty at monthly horizons and high spatial resolution, and are freely available for academic and public use.

---

## Overview

This project includes:

```
local_temperature_uncertainty/
├── DATA/           # Raw data storage and processed datasets
├── functions/      # R functions and utilities
├── int_prods/      # Intermediate products and calculations
├── PLOTS/          # Generated plots and visualizations
├── TABLES/         # Output tables and results
├── README.md       # This documentation
└── .git/           # Git repository files
```


---

## Files

| File                | Description                                        |
|---------------------|----------------------------------------------------|
| `index_generator.R` | Script to generate the indexes                     |
| `index_data.csv`    | Daily index values (precomputed)                   |
| `example_usage.Rmd` | Sample usage: load data, plot, summarize           |
| `README.md`         | This documentation                                 |
| `.gitignore`        | Standard ignore file for R projects                |

---

## How to Use

1. **Clone the repo or download it**:

```bash
git clone https://github.com/franceschini-f/local_temperature_uncertainty.git
cd local_temperature_uncertainty
```

2. Open the folder in RStudio or VS Code with the R extension enabled.

3. Run the script `compute_index.R` (or whichever script is your main entry point) to generate the index:
    ```r
    source("compute_index.R")
    ```

4. Optional: Configure paths or parameters inside the script depending on your data location or desired region/timeframe.



## Citation

Please cite the associated working paper:

> Cavaliere, Giuseppe, Luca Fanelli and Fabio Franceschini (2025). *Local Indices of Physical Climate Uncertainty*. Working Paper. <!-- [Link to paper if available] -->



