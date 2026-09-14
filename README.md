# slp-iris-classifier# Single Layer Perceptron — Iris Setosa vs Versicolor

Assignment 1 (Single Layer Perceptron)

Binary classification of Iris Setosa (0) vs Versicolor (1) using a single-layer
perceptron with sigmoid activation, trained via per-sample (online) gradient
descent — reproducing the SLP-Training / SLP-Validation spreadsheet exactly.

- Epochs: 5
- Learning rate: 0.1
- Loss: Sum Squared Error
- Training samples: 80 | Validation samples: 20

## Files
- `slp_iris.py` — standalone script
- `slp_iris.ipynb` — same code, runnable notebook with inline charts
- `epoch_metrics.csv` — per-epoch train/val accuracy & loss
- `outputs/` — accuracy and loss charts

## Run
\`\`\`
pip install -r requirements.txt # Only if u have not installed mathplotlib
python slp_iris.py
\`\`\`
