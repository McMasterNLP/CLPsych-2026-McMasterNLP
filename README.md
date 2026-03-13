# CLPsych 2026 - McMaster NLP

## Data Preprocessing

This repository contains scripts for preprocessing CLPsych timeline data.

### Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd CLPsych-2026-McMasterNLP
```

2. Download the dataset into the repository directory

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

### Usage

Run all cells in the `preprocess_data.ipynb` notebook to process the data:

```bash
jupyter notebook preprocess_data.ipynb
```

Or open the notebook in VS Code and run all cells.

### Output

The preprocessing script will generate:
- `dataset_statistics.png` - Statistical visualization of the dataset
- `csv_files/` - Individual CSV files for each timeline
- `all_timelines_merged.csv` - Merged CSV file with all timelines

### Dataset Statistics

![Dataset Statistics](../dataset_statistics.png)

The visualization shows:
- Post count distribution across timelines
- Box plot of post counts
- Top 20 timelines by post count
- Summary statistics (total timelines, posts, averages, etc.)
