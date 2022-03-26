# riverdistパッケージの使い方

Rパッケージの`riverdist`の基本的な使い方を載せました。
シェープファイルは乗せていませんので、各自データをダウンロードしてご使用ください。

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