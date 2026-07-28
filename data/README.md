# Dataset

This folder contains the datasets required to run the notebook.

Contents:

- `train.csv`
- `test.csv`

Do not rename or move these files, as the notebook loads them using:

```python
pd.read_csv("data/train.csv")
pd.read_csv("data/test.csv")
```
