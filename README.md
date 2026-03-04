## End-to-End Machine Learning Project

This repository contains a complete end-to-end machine learning workflow implemented in Python. The code demonstrates data ingestion, transformation, model training, and prediction using a structured `src` package, with support for serving via simple web templates.

Key features:
- **Data Pipeline:** Modular components for ingestion and transformation (`src/components`).
- **Training Pipeline:** Scriptable training flow with `train_pipeline.py`.
- **Prediction Pipeline:** Reusable inference logic in `predict_pipeline.py`.
- **Modeling:** Uses CatBoost for classification/regression (training artifacts stored in `artifacts/`).
- **Web Interface:** Basic Flask templates under `templates/` for quick demonstrations.

## Project Structure

```
app.py                # entry point for running app/pipelines
src/                  # source package with components and utilities
artifacts/            # generated data and model files
notebook/             # exploratory analysis and experiments
logs/                 # logging output
```

## Tech Stack

- Python 3.x
- CatBoost
- Flask (for simple UI)
- pandas, scikit-learn utilities

