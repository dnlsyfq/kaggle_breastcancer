```
import pandas as pd
from sklearn.datasets import load_breast_cancer

cancer_data = load_breast_cancer(as_frame=True)
cancer_df = cancer_data['data']
cancer_df['target'] = cancer_data['target'] # target stores the value 0 if the tumor is benign or 1 if the tumor is malignant.

print(cancer_df.head())
```
