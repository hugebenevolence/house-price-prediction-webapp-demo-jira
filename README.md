# House Price Prediction Webapp Demo Jira

Minimal demo project for testing Jira and GitHub development activity links.

Baseline training script added for Jira integration demo.

## Project Structure

```text
house-price-prediction-webapp-demo-jira/
├── README.md
├── requirements.txt
├── src/
│   ├── load_data.py
│   ├── preprocess.py
│   ├── train_baseline.py
│   └── evaluate.py
├── app/
│   └── main.py
└── reports/
    └── figures/
```

## Run Baseline Training

```bash
pip install -r requirements.txt
python src/train_baseline.py
```

## Baseline Results

```text
R^2: 0.5758
MAE: 0.5332
RMSE: 0.7456
```
