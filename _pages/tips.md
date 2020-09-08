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

## R
データ解析に使用

便利なパッケージ
- tidyverse: データ処理
- zoo: 時系列データのNA処理
- lme4: GLMM
- ggthemes: ggplotのテーマ. theme_mapをよく使う.

## website
- [論文ネットワーク](https://www.connectedpapers.com/)
  分野の重要な文献を見つけやすい．使うと楽しい．

## Camera
For high-resolution movie
- [DFK33UX183](https://www.argocorp.com/cam/usb3/tis/DxK33UX183.html)
