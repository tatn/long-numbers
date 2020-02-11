# 数学定数の数表(10桁、100桁、1000桁、10000桁、…)

## 説明

「{定数の名前}_{小数点以下桁数}.txt」が各定数を記載したテキストファイル。

「{定数の名前}_{小数点以下桁数}.pickle」がpythonのpickleで固めたファイル。サンプルは以下。

```python
with open('pi_100.pickle', 'rb') as f:
    pi = pickle.load(f)

print(pi)
```

## π、円周率、アルキメデスの定数、ルドルフ数

https://github.com/tatn/long-numbers/tree/master/pi

## φ、τ、黄金比

https://github.com/tatn/long-numbers/tree/master/golden-ratio

## e、ネイピア数、オイラー数、自然対数の底 

https://github.com/tatn/long-numbers/tree/master/napiers-constant
