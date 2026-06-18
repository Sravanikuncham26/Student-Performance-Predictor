# Student Performance Predictor

Predict students' final marks using academic and personal features. This project includes a Jupyter Notebook that generates a synthetic dataset, runs EDA, trains regression models, evaluates them, and saves the best model.

## Files

- Student_Performance_Predictor.ipynb: Main notebook with full implementation.
- student_performance.csv: Generated when running the notebook (saved to working directory).
- student_performance_model.pkl: Saved after training the best model (created when you run the notebook).
- requirements.txt: Python dependencies.

## How to run

1. Create a Python environment and install dependencies:

```bash
pip install -r requirements.txt
```

2. Launch Jupyter Notebook and open the notebook:

```bash
jupyter notebook Student_Performance_Predictor.ipynb
```

3. Run cells top-to-bottom. The notebook will generate `student_performance.csv` and save `student_performance_model.pkl` when executed.

## Notes

- The dataset is synthetic and generated deterministically with a fixed random seed for reproducibility.
- To use this in production, replace the synthetic data generation with a real dataset and consider model validation strategies (cross-validation, hyperparameter tuning).

## Future Work

- Add classification for pass/fail, deploy via Streamlit or Flask, and try advanced models like XGBoost or deep learning.
