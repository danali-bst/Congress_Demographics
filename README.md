# Congress_Demographics

# Congress Demographics Trends

This repository contains the analysis and data (https://data.fivethirtyeight.com/) used to reproduce trends in Congress demographics, inspired by a FiveThirtyEight article (https://fivethirtyeight.com/features/aging- congress-boomers/). The primary goal of this project is to explore generational shifts and trends in congressional representation over time.

## Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Data Sources](#data-sources)
- [Reproducibility](#reproducibility)
- [License](#license)

---

## Overview

This project uses R to analyze and visualize data about Congress demographics, including generational representation and historical trends. The analysis is documented in an R Markdown file and includes:

- Data preprocessing and cleaning.
- Exploratory data analysis.
- Visualizations of trends over time.

## Repository Structure

```
congress-demographics
├── analysis                # Analysis files and data
│   ├── data_aging_congress.csv
│   ├── updated_largest_generation_data.csv
│   ├── processed_congress_data_time.csv
│   ├── BST270_Congress_Trends_538_Reproduce.Rmd
├── output                  # Outputs generated from the analysis
│   ├── BST270_Congress_Trends_538_Reproduce.pdf
├── docs                    # Documentation or additional files
├── README.md               # This README file
├── .gitignore              # Git ignore file
└── LICENSE                 # License for the repository
```

## Getting Started

### Prerequisites

Make sure you have R and RStudio installed on your system. You also need the following R packages:

- `tidyverse`
- `ggplot2`
- `dplyr`
- `readr`
- Any additional packages listed in the R Markdown file.

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/danali-bst/congress-demographics.git
   ```

2. Navigate to the project directory:

   ```bash
   cd congress-demographics
   ```

3. Install the required R packages by running:

   ```R
   install.packages(c("tidyverse", "ggplot2", "dplyr", "readr"))
   ```

## Data Sources

- `data_aging_congress.csv`: Dataset containing aging data of Congress members.
- `updated_largest_generation_data.csv`: Updated data for generational analysis.
- `processed_congress_data_time.csv`: Preprocessed data for time-based analysis.

All data files are stored in the `analysis` folder.

## Reproducibility

To reproduce the analysis:

1. Open `BST270_Congress_Trends_538_Reproduce.Rmd` in RStudio (located in the `analysis` folder).
2. Render the file to HTML or PDF using the Knit button.
3. Outputs will be generated in the `output` folder.

Alternatively, use the following R command:

```R
rmarkdown::render("analysis/BST270_Congress_Trends_538_Reproduce.Rmd")
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to contribute or raise issues if you encounter any problems!


