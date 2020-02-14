---
title: "Kaggle: House Prices Prediction"
date: 2020-02-03
tags: [multiprocessing, paralell, R, Python]
---

Step01: python -m venv my_env
Step02: my_env\Scripts\activate
Step03: pip install ipykernel
Step04: python -m ipykernel install --user --name my_env --display-name "my_env" (run once)
Step05: jupyter notebook

```python
# Install libraries

#!pip install pandas numpy matplotlib seaborn 
#!pip install plotly
#!pip install nbformat
```

```python

# Import libraries

import pandas as pd
pd.set_option('display.max_rows', 50)
import numpy as np
from matplotlib import pyplot as plt
import seaborn as sns
%matplotlib inline
import matplotlib
import datetime as dt
from datetime import datetime, timedelta


import warnings
warnings.filterwarnings("ignore")

import plotly
import plotly.graph_objects as go
import plotly.express as px
import plotly.offline as py

plotly.offline.init_notebook_mode(connected=True)

```



```python
# Read dataset

df = pd.read_csv("../_dataset/ecommerce_dataset.csv", encoding="latin1")

df['InvoiceDate'] = pd.to_datetime(df['InvoiceDate'])
df['Date'] = df['InvoiceDate'].dt.date
df['Month'] = df['InvoiceDate'].dt.month
df['Year'] = df['InvoiceDate'].dt.year

df.head()

```



```python


```


```python


```


```python


```
