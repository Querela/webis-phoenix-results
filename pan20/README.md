# PAN20-small custom split

## Results

|Method|Acc|c@1|F1|
|---|---|---|---|
|Majority|0.5309|0.5309|0.6936|
|Unsupervised Similarity|0.4690|0.4690|0.0000|
|Supervised Similarity|0.5291|0.5291|0.6737|
|Imposters|0.4747|0.4747|0.0946|
|General Imposters|0.4748|0.4748|0.0985|
|StyleBird|0.8853|0.8853|0.8911|

## Reproduce split:

```python
X_train, X_test, y_train, y_test, ids_train, ids_test = train_test_split(X, y, ids, random_state=3397, shuffle=True, train_size=0.8)
```

## Evaluate your run:

```bash
python cmd/phoenix_eval.py av example.run results/pan20/pan20.truth
``` 