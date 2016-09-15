# ane

TSVやCSVをカラムベースで簡易的に編集するスクリプトです。awkやrubyのワンライナーよりもうちょっとだけ手軽に。


## 例

入力：

```
hoge, moge, sage
```

実行コマンド：

```
ane '\3 = \2 + \1' ,
```

出力：

```
sage = moge + hoge


```
Usage  : ane TEMPLATE [DELIMITER]
Example: ane 'UPDATE \1 SET \2 = \3;'
```
