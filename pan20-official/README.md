# PAN20-small custom split

## Results

|Method|Acc|F1|
|---|---|---|
|Majority|0.5440|0.7047|
|Unsupervised Similarity|0.4559|0.0000|
|Supervised Similarity|0.5440|0.6860|
|Imposters|-|-|
|Unmasking (Random Sampling)|-|-|
|StyleBird|0.8626|0.8737|

## Evaluate your run:

```bash
python cmd/phoenix_eval.py av results/pan20-official/pan20-test.truth example.run
``` 