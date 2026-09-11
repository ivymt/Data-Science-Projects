# Data Science Projects

A collection of data science projects covering exploratory data analysis (EDA), data cleaning, and visualization, preprocessing, machine learning, deep learning built while learning and practicing core data science skills.

## Projects

| Project | Description | Status |
|---|---|---|
| [Project1_Cars](Project1_Cars/mtcars.ipynb) | Exploratory data analysis of the [mtcars dataset](https://www.kaggle.com/code/mmrayhan/mtcars/input): inspecting, cleaning, summarizing, and visualizing relationships between car attributes (mpg, weight, horsepower, etc.) | Complete |
| [Project2_Iris](Project2_Iris) | Analysis of the Iris dataset | In progress |

### Project1_Cars — mtcars EDA

Walks through a full EDA workflow on the mtcars dataset:

1. Inspecting the data (shape, dtypes, head/tail)
2. Cleaning (removing duplicates, checking for nulls)
3. Retrieving/subsetting data (`loc`, `iloc`, filtering)
4. Statistical summaries and correlation analysis
5. Visualizations (distribution plots, regression plots) with findings, e.g. a negative correlation between `mpg` and `wt`

## Tech Stack

- Python
- pandas
- seaborn / matplotlib
- Jupyter Notebook

## Getting Started

```bash
# create and activate a virtual environment
python -m venv .venv
.venv\Scripts\activate      # Windows
source .venv/bin/activate   # macOS/Linux

# install dependencies
pip install pandas seaborn matplotlib jupyter

# launch Jupyter
jupyter notebook
```

Each project lives in its own folder with its notebook and dataset.

## Author

Ivy Mutodi
