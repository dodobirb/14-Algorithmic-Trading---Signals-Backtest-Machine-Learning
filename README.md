# Module_14_Challenge: Algorithmic Trading

FinTech Company X's existing trading algorithms have put us ahead of the competition. However, people still need to specifically program these systems, which limits their ability to adapt to new data. Thus, the existing algorithmic trading systems have been improved in order to maintain the firm’s competitive advantage in the market. The existing trading signals have been enhanced with machine learning algorithms that can adapt to new data. The input parameters have been adjusted to optimize the trading algorithm, and a new machine learning model can be trained to compare its performance to that of the baseline model.

---

## Technologies

This application was written in Python 3.9.4 on a Windows PC.

Google Colab may serve as the most ideal IDE with which to run the models in this program, given the implications of boosted performance and decreased training time of machine learning models. However, as these models are relatively simple, this program can still be run in your environment of choice.

---

## Installation Guide

Ensure through your local terminal that your development environment supports the following imports and dependencies:

```
import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report
from sklearn.linear_model import LogisticRegression
```

If it does not, reference your terminal installation guide to download the missing software.

---

## Contributors

Brought to you by financial advisor Erin Kenny at FinTech Company X.

ekenny3@uncc.edu

www.linkedin.com/in/e-kenny

---

## License

MIT

License file included in repository.

---

## Summary Evaluation Report

*For this report, express your final conclusions and analysis. Support your findings by using the PNG images that you created.*



![SVM Actual vs. Strategy Plot](./Resources/svm_actual_vs_strategy_plot.png)

![Logistic Regression Actual vs. Strategy Plot](./Resources/lr_actual_vs_strategy_plot.png)