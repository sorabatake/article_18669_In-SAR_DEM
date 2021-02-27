# article_18669_In-SAR_DEM
日本発の衛星データプラットフォーム Tellus のオウンドメディア「宙畑」の記事、https://sorabatake.jp/18669 で利用しているコードです。

干渉SAR解析の中でも、DEM（標高モデル）を使って地形縞の除去にチャレンジします。
**コードの実行には、Tellusの開発環境が必要です。**

## 構成
- In-SAR_DEM.ipynb
　メインのソースコード
- ALPSMLC30_N035E138_DSM.tif
  今回使ったAW3DのDEM

## ライセンス、利用規約
ソースコードのライセンスは CC0-1.0（Creative Commons Zero v1.0 Universal）ライセンスです。  
今回コード内で PALSAR-2およびAW3D30 データを用いております。利用ポリシーは以下をご参考下さい。

- PALSAR-2
https://www.tellusxdp.com/market/tool_detail/de3c41ac-a8ca-4170-9028-c9e1a39841e1/e364c31c-bfad-49d0-bd6d-f2bc11d67386
（Tellusへのログインが必要です。）

- AW3D30
https://www.eorc.jaxa.jp/ALOS/aw3d30/index_j.htm#section_5

## 貢献方法
プルリクエストや Issue はいつでも歓迎します。
