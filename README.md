# riverdistパッケージの使い方

Rパッケージの`riverdist`の基本的な使い方を載せました。
サンプルコード中 (`river_dist_calc.Rmd`) で使用しているのは[北海道のシェープファイル](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-W05.html#prefecture01)です。
シェープファイルは掲載していませんので、各自データをダウンロードしてご使用ください。
htmlレポート`river_dist_calc.html`も掲載しているので、そちらもご参照ください。

```{shell}
# ディレクトリ構成
.
├── Environment.Rproj # ディレクトリ
├── README.md
├── W05-09_01_GML # shapefileはダウンロードしてください
│   ├── KS-META-W05-09_01-g.xml
│   ├── W05-09_01-g.xml
│   ├── W05-09_01-g_RiverNode.dbf
│   ├── W05-09_01-g_RiverNode.shp
│   ├── W05-09_01-g_RiverNode.shx
│   ├── W05-09_01-g_Stream.dbf
│   ├── W05-09_01-g_Stream.shp
│   └── W05-09_01-g_Stream.shx
├── pointdata.csv # 距離を算出したい2地点の座標データを収録
├── report # Rmdファイルから生成されるレポート
│   └── river_dist_calc.html
└── river_dist_calc.Rmd # コード
```
