# First MLOps pipeline

Train a classifier on the Iris dataset and save the artifact. This is the first step of the deployment course at EMSI: one reproducible script, before experiment tracking.

## Run

```bash
conda env create -f environment.yml
conda activate mlops_base_env
python train.py
```

The model is written to `models/iris_model.pkl`. The test score is printed at the end.
