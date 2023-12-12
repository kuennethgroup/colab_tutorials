# Prepare for the 1st hackathon


### General
- [ ] Fill out [this](../lecture6/example_README.md) and upload to your own folder at coder
- [ ] Make sure you can connect to your coder instance using VScode
- [ ] Connect your folder on the coder VM with your GitHub account

### Data
- [ ] Upload your data to the your coder VM (e.g., use vscode) 
- [ ] OR generate a synthetic dataset using Python
- [ ] Make sure you can load the dataset with `pd.read_pickle('my_dataset.pkl')`.
- [ ] Create a file `data.ipynb` that contains the code to load the data and split it to 80% (train) and 20% (test)
- [ ] Talk to Chris (if you have not done so)

Example for `data.ipynb`
```python
import pandas as pd

df = pd.read_pickle('my_dataset.pkl')
display(df)
df_train, df_test = train_test_split(df, test_size=0.2, random_state=1)
len(df), len(df_train), len(df_test)

```


