# README.md
サッカー選手の成績を解析するリポジトリです。

## 階層の説明
- code
  - データ解析のメインリソースを格納します
  - ./data/のCSVを読み込んで実装を進めます
  - 言語は主にPythonで実装します
- data
  - 選手成績を下記URLから指定しCSV形式で出力します
  - https://fbref.com/en/
- image
  - 出力するグラフの可視性を高めるために用います
- output
  - ./code/で解析された結果が出力されます

## 参考実装例
- Radar Charts Official

https://github.com/Slothfulwave612/soccerplots/blob/master/docs/radar_chart.md#examples

- Nunez-vs-Haaland-Radar-Plot

https://github.com/arinzecode/Nunez-vs-Haaland-Radar-Plot/blob/main/Nunez%20vs%20Haaland%20Radar%20Plot.ipynb

## 起動
```
$ jupyter-notebook
http://localhost:8888/?token=XXXXXXXXXX ⇐ブラウザで開いて実装していきます
```