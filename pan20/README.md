# PAN20-small custom split

## Results

|Method|Acc|c@1|F1|
|---|---|---|---|
|StyleBird|0.8853|0.8853|0.8911|

## Reproduce split:

```python
X_train, X_test, y_train, y_test, ids_train, ids_test = train_test_split(X, y, ids, random_state=3397, shuffle=True, train_size=0.8)
```

## Evaluate your run:

```bash
python cmd/phoenix_eval.py av example.run results/pan20/pan20.truth
``` 