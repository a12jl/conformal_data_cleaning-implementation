# Conformal Data Cleaning (CDC) – Reproduction

CDC trains one model per column to predict its value from the other columns, calibrates the predicted range with conformal prediction (conformalized quantile regression), and replaces values that fall outside the range with the model's prediction.

## Files
| File | Description |
|---|---|
| `CDC_Implementation.ipynb` | The implementation and the experiment (with outputs) |
| `requirements.txt` | Required Python packages |

## How to run
1. Install Python 3.9 or newer.
2. Install the packages: pip install -r requirements.txt
3. The full run takes around 3 minutes to execute.
