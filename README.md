hello there, this is my readme and ai will help me to generate it
# Housing Data Mining Project

A small data mining project based on the housing dataset in [Housing.csv](Housing.csv).  
The project is organized as two Jupyter notebooks:

- [tp1.ipynb](tp1.ipynb): dataset exploration and descriptive statistics
- [tp2.ipynb](tp2.ipynb): data visualization and relationship analysis

## Project Structure

- [Housing.csv](Housing.csv) — main dataset
- [tp1.ipynb](tp1.ipynb) — exploratory data analysis
- [tp2.ipynb](tp2.ipynb) — visual analysis and correlations
- [requirements.txt](requirements.txt) — Python dependencies
- [README.md](README.md) — project documentation

## Dataset Overview

The dataset contains **545 rows** and **13 columns**.

### Numerical Features

- `price`
- `area`
- `bedrooms`
- `bathrooms`
- `stories`
- `parking`

### Categorical Features

- `mainroad`
- `guestroom`
- `basement`
- `hotwaterheating`
- `airconditioning`
- `prefarea`
- `furnishingstatus`

## Main Observations

From the analysis in [tp1.ipynb](tp1.ipynb) and [tp2.ipynb](tp2.ipynb):

- The dataset has **no missing values**.
- The distributions of **price**, **area**, **bathrooms**, and **bedrooms** are generally **right-skewed**.
- The mean house price is about **4,766,729**.
- The median house price is **4,340,000**.
- There is a **moderate positive correlation** between `area` and `price`:

  $$r \approx 0.536$$

- There is a **weak positive correlation** between `bedrooms` and `price`:

  $$r \approx 0.366$$

- Houses with **air conditioning** tend to be more expensive.
- Furnishing level affects price in this order:

  $$\text{furnished} > \text{semi-furnished} > \text{unfurnished}$$

- The average price increases with the number of stories.

## Technologies Used

This project uses:

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

Dependencies are listed in [requirements.txt](requirements.txt).

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/issamsensi/Data-Mining-Tp.git
cd Data-Mining-Tp
```

### 2. Install dependencies

It is recommended to use a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```


## Author

Issam Sensi

## Portfolio

[issamsensi.com](https://issamsensi.com)