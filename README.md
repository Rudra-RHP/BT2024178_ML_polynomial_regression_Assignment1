Polynomial regression implementation using NumPy, including model training, cross-validation, and prediction for both datasets.

### Run

```bash
pip install -r requirements.txt
python train.py
python pred.py
```

Files
- polyreg.py - polynomial feature generation, Least Squares, Ridge, Lasso, and cross-validation
- train.py - model selection, cross-validation, and final model training
- pred.py - generates predictions for the test datasets
- requirements.txt - required Python packages
- BT2024178/ - training and test datasets
- models/ - saved trained models
- results/ - cross-validation results and plots
- BT2024178_pred_var1.csv - predictions for var1
- BT2024178_pred_var2.csv - predictions for var2
