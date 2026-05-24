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

=======

# Insurance Risk Analytics

End-to-end insurance risk analytics and predictive modeling project for AlphaCare Insurance Solutions (ACIS).

## Objectives

- Perform exploratory data analysis
- Conduct statistical hypothesis testing
- Build predictive models for claim severity and probability
- Develop risk-based pricing insights

## Project Structure
