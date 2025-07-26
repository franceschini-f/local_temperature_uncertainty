# Local Temperature Uncertainty Indexes

This repository contains R scripts to form the indexes for a set of **custom financial indexes** created using publicly available market data. These indexes are designed to capture key market features and are made freely available for public and academic use.

---

## Overview

This project includes:

- `0-data_intake.R`: An R script to calculate the indexes from raw data
- `1-data_filtering.R`: An R script to calculate the indexes from raw data
- `2-temp_pred.R`: An R script to calculate the indexes from raw data
- `3-unc_indexes_form.R`: An R script to calculate the indexes from raw data
- `main.Rmd`: A short R Markdown file showing how to load and explore the data

The indexes reflect [brief description here, e.g., "aggregate liquidity measures across sectors", "volatility adjusted for trading volume", etc.].

The methodology is based on [optionally cite a reference, your own method, or keep it general].

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
git clone https://github.com/YOUR_USERNAME/custom-indexes.git
cd custom-indexes
```


2. Open the folder in RStudio or VS Code with the R extension enabled.

3. Run the script `compute_index.R` (or whichever script is your main entry point) to generate the index:
    ```r
    source("compute_index.R")
    ```

4. Optional: Configure paths or parameters inside the script depending on your data location or desired region/timeframe.



## Citation

Please cite the associated working paper:

> Cavaliere, Giuseppe, Luca Fanelli and Fabio Franceschini (2025). *Local Temperature Uncertainty*. Working Paper. <!-- [Link to paper if available] -->



