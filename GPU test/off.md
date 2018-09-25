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
Label enconding processes in 31.020089 seconds
One-Hot encoding processes in 2.501879 seconds
(313864, 1190)
Fitting 4 folds for each of 5 candidates, totalling 20 fits
[CV] colsample_bytree=0.67, gamma=0.9, learning_rate=0.001, max_depth=9, min_child_weight=50, n_estimators=1500, nthread=-1, objective=<function logregobj at 0x0000019C1C89C1E0>, seed=1234, subsample=0.78 
[CV]  colsample_bytree=0.67, gamma=0.9, learning_rate=0.001, max_depth=9, min_child_weight=50, n_estimators=1500, nthread=-1, objective=<function logregobj at 0x0000019C1C89C1E0>, seed=1234, subsample=0.78, score=-1631.93647431623, total= 8.7min
[Parallel(n_jobs=1)]: Done   1 out of   1 | elapsed:  8.8min remaining:    0.0s
[CV] colsample_bytree=0.67, gamma=0.9, learning_rate=0.001, max_depth=9, min_child_weight=50, n_estimators=1500, nthread=-1, objective=<function logregobj at 0x0000019C1C89C1E0>, seed=1234, subsample=0.78 
[CV]  colsample_bytree=0.67, gamma=0.9, learning_rate=0.001, max_depth=9, min_child_weight=50, n_estimators=1500, nthread=-1, objective=<function logregobj at 0x0000019C1C89C1E0>, seed=1234, subsample=0.78, score=-1652.3073303726185, total= 8.9min
[Parallel(n_jobs=1)]: Done   2 out of   2 | elapsed: 17.9min remaining:    0.0s
[CV] colsample_bytree=0.67, gamma=0.9, learning_rate=0.001, max_depth=9, min_child_weight=50, n_estimators=1500, nthread=-1, objective=<function logregobj at 0x0000019C1C89C1E0>, seed=1234, subsample=0.78 
[CV]  colsample_bytree=0.67, gamma=0.9, learning_rate=0.001, max_depth=9, min_child_weight=50, n_estimators=1500, nthread=-1, objective=<function logregobj at 0x0000019C1C89C1E0>, seed=1234, subsample=0.78, score=-1642.0154080097066, total= 8.7min
[Parallel(n_jobs=1)]: Done   3 out of   3 | elapsed: 26.7min remaining:    0.0s
[CV] colsample_bytree=0.67, gamma=0.9, learning_rate=0.001, max_depth=9, min_child_weight=50, n_estimators=1500, nthread=-1, objective=<function logregobj at 0x0000019C1C89C1E0>, seed=1234, subsample=0.78 
[CV]  colsample_bytree=0.67, gamma=0.9, learning_rate=0.001, max_depth=9, min_child_weight=50, n_estimators=1500, nthread=-1, objective=<function logregobj at 0x0000019C1C89C1E0>, seed=1234, subsample=0.78, score=-1643.592146330731, total= 8.7min
[Parallel(n_jobs=1)]: Done   4 out of   4 | elapsed: 35.6min remaining:    0.0s
[CV] colsample_bytree=0.67, gamma=0.9, learning_rate=0.01, max_depth=9, min_child_weight=50, n_estimators=1500, nthread=-1, objective=<function logregobj at 0x0000019C1C89C1E0>, seed=1234, subsample=0.78 
[Cancelled]
```
It took too long that I manually canceled.
