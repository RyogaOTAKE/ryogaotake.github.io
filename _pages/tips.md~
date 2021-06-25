---
permalink: /tips/
title: "tips"
excerpt: "tips"
author_profile: true
---

研究関連のちょっと役に立つもの

## 正規表現

```
# a の後にa~zの文字がくるもの
a[a-z]

# aの後にa~z以外がくるもの
a[^a-z]
```

## ffmpeg
動画の処理に使用

```
# 動画の情報を見る
ffmpeg -i input.avi

# 動画を静止画に切り出し
ffmpeg -i input.avi -qscale 1 out%05d.png

# 動画 60秒目から30秒間切り出す(画質維持)
ffmpeg -ss 60 -i input.avi -qscale 0 -t 30 output.avi

# RGB -> grayscale (BT.601)
-vf colorchannelmixer=.299:.587:.114:0:.299:.587:.114:0:.299:.587:.114:0

# change resolution, -1 -> auto setting
ffmpeg -i input.mp4 -vf scale=1280:-1 out.mp4

# change fps: -r 10 -> 10 fps
ffmpeg -i exapmle.avi -r 10 exapmle.mp4

```

## shell
```
# path以下の特定の拡張子のファイルをコピー
find /path/ -type f -name "*.txt" -exec cp {} /path/ \;
```

## R
データ解析に使用

便利なパッケージ
- tidyverse: データ処理
- zoo: 時系列データのNA処理
- lme4: GLMM
- ggthemes: ggplotのテーマ. theme_mapをよく使う.

'''
#日本語フォントのpdf保存できない問題
#svgで保存してイラレで編集する
library(svglite)
ggsave("file_name.svg", graph, width = 8, height = 8)
'''

## website
- [Connected Papers](https://www.connectedpapers.com/)
  分野の重要な文献を見つけやすい．使うと楽しい．
- [Zotero styles](https://www.zotero.org/styles)
  ジャーナルごとのcslファイルをダウンロードできる

## Camera
For high-resolution movie
- [DFK33UX183](https://www.argocorp.com/cam/usb3/tis/DxK33UX183.html)

## データディスク
全てex-FATにする
- [seagate HDD 8TB](https://www.amazon.co.jp/dp/B07911QK3X/ref=cm_sw_em_r_mt_dp_y1hwFbX161BVS)
  [この辺](https://www.century.co.jp/products/pc/razoku/)のものと一緒に使用

- [sandisk SSD 2TB](https://www.amazon.co.jp/dp/B07CYC2VQ5/ref=cm_sw_em_r_mt_dp_G0hwFbP7FJ6AG)

## 日本語の書き方
本多勝一「日本語の作文技術」より

> 修飾の順序
>  - 節を先にして，句を後にする．
>  - 長いものを先にして，短いものを後にする．
>  - 大状況・重要内容ほど先にする．
>  - 親和度（なじみ）の強弱により配置転換する．

> 句読点の打ち方
>  - 必要最小限のテンだけを打つ．
>  - 長い修飾語が二つ以上あるとき，その境界にテンを打つ．
>  - 語順が，修飾語の語順の原則に照らして逆順の場合にテンを打つ．

> その他
>  - 紋切型の文章はダサい．
>  - 体言止めの文章は下品だ．

