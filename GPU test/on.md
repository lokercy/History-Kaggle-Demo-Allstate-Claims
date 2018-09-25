# GPU acceleration off

## PC info
- Xiaomi Mi Book Air 2018
- CPU i5-9250U
- GPU GTX MX 150, Pascal micro-architecture compute, capability version 6.1

## Console log:

```
C:\Users\Craig\AppData\Local\Programs\Python\Python37\lib\site-packages\sklearn\ensemble\weight_boosting.py:29: DeprecationWarning: numpy.core.umath_tests is an internal NumPy module and should not be imported. It will be removed in a future NumPy release.
  from numpy.core.umath_tests import inner1d
E:\GitHub\History-Kaggle-Demo-Allstate-Claims\preprocess_GridSearch.py:74: FutureWarning: Sorting because non-concatenation axis is not aligned. A future version
of pandas will change to not sort by default.

To accept the future behavior, pass 'sort=False'.

To retain the current behavior and silence the warning, pass 'sort=True'.

  full_data = pd.concat([df_train, df_test]).reset_index(drop=True)
Full Data set created.
Label enconding processes in 31.564509 seconds
One-Hot encoding processes in 2.366046 seconds
(313864, 1190)
Fitting 4 folds for each of 5 candidates, totalling 20 fits
[CV] colsample_bytree=0.67, gamma=0.9, learning_rate=0.001, max_depth=9, min_child_weight=50, n_estimators=1500, nthread=-1, objective=<function logregobj at 0x000001FE3F59C1E0>, seed=1234, subsample=0.78 
[Finished in 120.5s]
```

## Error
Sometimes it exits with stack overflow.
