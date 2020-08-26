---
permalink: /tips/
title: "tips"
excerpt: "tips"
author_profile: true
---

研究関連のちょっと役に立つもの

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

```

## R
データ解析に使用

便利なパッケージ
- tidyverse: データ処理
- zoo: 時系列データのNA処理
- lme4: GLMM
- ggthemes: ggplotのテーマ. theme_mapをよく使う.


## Camera
For high-resolution movie
- [DFK33UX183](https://www.argocorp.com/cam/usb3/tis/DxK33UX183.html)
