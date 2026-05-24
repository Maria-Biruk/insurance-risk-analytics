## Data Version Control (DVC)

This project uses DVC to track datasets and ensure reproducibility.

### How to reproduce data pipeline

```bash
git clone <repo>
cd insurance-risk-analytics

pip install -r requirements.txt
dvc pull

# raw data
data/insurance_data.csv

# cleaned data
data/insurance_data_cleaned.csv
```
