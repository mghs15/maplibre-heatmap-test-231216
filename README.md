
## 必要なデータ
* Maplibre のJavaScript/CSS ファイル
* 表示用のデータ

## 結果の分析用の R コマンド
```
fm <- df$idle ~ df$treatment
boxplot(fm, xlab="処理", ylab="時間（ミリ秒）")
t.test(fm)
```

