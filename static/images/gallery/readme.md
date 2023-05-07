# image resize
fullsの方は元データで良いと思うがthumbsの方は360x250にリサイズ＆トリミングが必要

```
gallery % identify thumbs/01.jpg
thumbs/01.jpg JPEG 360x250 360x250+0+0 8-bit sRGB 36286B 0.000u 0:00.002
```

## 面倒な時は
GIMPでいい感じに作るのが良いと思うが、面倒な時はコマンドで簡単にcropしちゃおう。

> convert orijinal.png -crop 360x250+50+50  output.png

50+50の所はcrop開始点なので画像のおおまかな位置を指し示すと良いかも。


