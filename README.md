# Max的花園 Max Hana

分享花園明朝字體的相關改作字型。

## B2花園 (B2 Hana)
B2花園字體基於花園明朝的轉角的三角形轉成半圓形改造，彷彿墨暈或是稍微過曝的效果。可以免費商用，歡迎大家自由應用、自由優化、自由改作！
![B2花園字體預覽](https://github.com/max32002/max-hana/raw/master/preview/welcome_b2hana.png)

B2花園與花園明朝字體比較：
![B2花園字體比較預覽](https://github.com/max32002/max-hana/raw/master/preview/compare_hana_b2.png)

附註：Regular 字重，是直接來自花園明朝，Medium 字重是透過程式產生，不能確定所有的字都正常，可能會轉換失敗。

## 花園肉丸 (Hana Meatball)
花園肉丸字體基於花園明朝的三角形換半圓形改造，遊走於古典與可愛之間的字體。可以免費商用，歡迎大家自由應用、自由優化、自由改作！
![花園肉丸字體預覽](https://github.com/max32002/max-hana/raw/master/preview/welcome_hahameatball.png)

花園肉丸與花園明朝字體比較：
![花園肉丸字體比較預覽](https://github.com/max32002/max-hana/raw/master/preview/compare_hana_meatball.png)

附註：Regular 字重，是直接來自花園明朝，Medium 字重是透過程式產生，不能確定所有的字都正常，可能會轉換失敗。


## 檔案說明
* HanaMinA.ttf 花園明朝字體A+G區。原版的花園明朝只有A區。
* HanaMinB.ttf 花園明朝字體B-F區。
* B2Hana-Regular.ttf B2花園 Regular 字重
* B2Hana-Regular.ttf B2花園 Medium 字重 (線條較粗)
* B2HanaB-Regular.ttf B2花園（B-F區） Regular 字重
* B2HanaB-Regular.ttf B2花園（B-F區） Medium 字重 (線條較粗)
* HanaMeatball-Regular.ttf B2花園 Regular 字重
* HanaMeatball-Regular.ttf B2花園 Medium 字重 (線條較粗)

附註1：一般情況下，使用 A區就可以了，常用字在A區，其他區的字比較少使用到。
附註2：為什麼要分成2個字型檔？因為單一字型檔有字數的上限，所以需要分成2個。

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」，或點進想下載的ttf字型檔案，再點「Download」的按鈕進行下載。

## 網頁字型(Web Font)服務

網頁字型用於網頁上的字型顯示，訪客不需預先安裝字型檔，一樣能夠看到特殊的字型效果。不只是電腦，在智慧型手機和平板裝置的瀏覽器上也可正常顯示。實現該功能的原理是在瀏覽時才下載字型檔。

花園明朝A＋G區可以服用下面的css:
```
@font-face {
  font-family: HanaMinA;
  src: url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/HanaMinA.woff2) format("woff2")
  , url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/HanaMinA.woff) format("woff");
}
```

B2花園Regular（精簡版，只有常用字）,可以服用下面的css:
```
@font-face {
  font-family: B2Hana-Regular;
  src: url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/B2Hana-Regular-Lite.woff2) format("woff2")
  , url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/B2Hana-Regular-Lite.woff) format("woff");
}
```
B2花園A區Regular（完整版）,可以服用下面的css:
```
@font-face {
  font-family: B2Hana-Regular;
  src: url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/B2Hana-Regular.woff2) format("woff2")
  , url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/B2Hana-Regular.woff) format("woff");
}
```
B2花園A區Medium,可以服用下面的css:
```
@font-face {
  font-family: B2Hana-Medium;
  src: url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/B2Hana-Medium.woff2) format("woff2")
  , url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/B2Hana-Medium.woff) format("woff");
}
```
花園肉丸A區Regular（精簡版，只有常用字）,可以服用下面的css:
```
@font-face {
  font-family: HanaMeatball-Regular;
  src: url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/HanaMeatball-Regular-Lite.woff2) format("woff2")
  , url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/HanaMeatball-Regular-Lite.woff) format("woff");
}
```
花園肉丸A區Regular（完整版）,可以服用下面的css:
```
@font-face {
  font-family: HanaMeatball-Regular;
  src: url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/HanaMeatball-Regular.woff2) format("woff2")
  , url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/HanaMeatball-Regular.woff) format("woff");
}
```
花園肉丸A區Medium,可以服用下面的css:
```
@font-face {
  font-family: HanaMeatball-Medium;
  src: url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/HanaMeatball-Medium.woff2) format("woff2")
  , url(https://cdn.jsdelivr.net/gh/max32002/max-hana@1.1/webfont/HanaMeatball-Medium.woff) format("woff");
}
```

## 附註
* B2花園字體的演算黑科技，將字體轉角的三角形轉成半圓形，請參考獅尾B2宋朝專案下的 /python/ 目錄下的腳本檔案。透過調整程式碼，也許也可以產生出新的有趣字型。目前的程式應該還有很多錯誤或需要再加強的地方。請先把要處理的字型，透過 FontForge 開啟，並另存 FontForge 的專案為資料夾格式(.sfdir)，最後就可以透過Max的 Python 程式去處理產生出來的檔案。
* 花園肉丸字體的演算黑科技，將字體轉角的三角形轉成半圓形，請參考獅尾肉丸專案下的 /python/ 目錄下的腳本檔案。透過調整程式碼，也許也可以產生出新的有趣字型。目前的程式應該還有很多錯誤或需要再加強的地方。請先把要處理的字型，透過 FontForge 開啟，並另存 FontForge 的專案為資料夾格式(.sfdir)，最後就可以透過Max的 Python 程式去處理產生出來的檔案。

## 著作權與授權

* 本字型是改造グリフウィキ(GlyphWiki)所開發、發表的「[花園明朝(花園フォントについて)](http://fonts.jp/hanazono/)」字型。
* 本字型亦基於 SIL Open Font License 1.1 授權條款免費公開，關於授權合約的內容、免責事項等細節，請詳讀 License 文件。
    * 可自由商用 不需付費、知會或標明作者，即可自由使用此字型，亦可做商業應用。
    * 可自由傳布 可自由分享檔案、將檔案安裝於任何軟硬體中。
    * 可自由改作為其他字型 將字型檔案修改重製為其他字型檔案，改作後的字型檔案須同樣依 Open Font License 釋出。
    
## 相關網頁

花園家族：
* B2花園 B2 Hana
https://max-everyday.com/2020/08/b2-hana-font/
* 花園肉丸 Hana Meatball
https://max-everyday.com/2020/08/hana-meatball/

獅尾黑體家族：
* 獅尾鋸齒黑體 Swei Alias Sans
https://max-everyday.com/2020/10/swei-alias-sans/
* 獅尾尖腿黑體 Swei Spike Leg
https://max-everyday.com/2020/10/swei-spike-leg/
* 獅尾尖刺黑體 Swei Spike Sans
https://max-everyday.com/2020/10/swei-spike-sans/
* 獅尾快腿黑體 Swei Shear Leg
https://max-everyday.com/2020/09/swei-shear-leg/
* 獅尾快剪黑體 Swei Shear Sans
https://max-everyday.com/2020/09/swei-shear-sans/
* 獅尾福腿黑體 Swei Gospel Leg
https://max-everyday.com/2020/09/swei-gospel-leg/
* 獅尾福音黑體 Swei Gospel Sans
https://max-everyday.com/2020/09/swei-gospel-sans/
* 獅尾D滷腿黑體 Swei Del Luna Leg
https://max-everyday.com/2020/09/swei-del-luna-leg/
* 獅尾德魯納黑體 Swei Del Luna Sans
https://max-everyday.com/2020/09/swei-del-luna-sans/
* 獅尾彎腿黑體 Swei Curve Leg
https://max-everyday.com/2020/09/swei-curve-leg/
* 獅尾彎黑體 Swei Curve Sans
https://max-everyday.com/2020/09/swei-curve-sans/
* 獅尾霓腿黑體 Swei Bow Leg
https://max-everyday.com/2020/09/swei-bow-leg/
* 獅尾霓黑體 Swei Bow Sans
https://max-everyday.com/2020/09/swei-bow-sans/
* 獅尾蝙蝠圓體 Swei Bat Sans
https://max-everyday.com/2020/09/swei-bat-sans/
* 獅尾牙膏圓體 Swei Toothpaste
https://max-everyday.com/2020/09/swei-toothpaste/
* 獅尾三腿黑體 Swei 3T Leg
https://max-everyday.com/2020/09/swei-3t-leg/
* 獅尾三角黑體 Swei 3T Sans
https://max-everyday.com/2020/08/swei-3t-sans/
* 獅尾螺帽腿黑體 Swei Nut Leg
https://max-everyday.com/2020/08/swei-nut-leg/
* 獅尾螺帽黑體 Swei Nut Sans
https://max-everyday.com/2020/08/swei-nut-sans/
* 獅尾B2腿黑體 Swei B2 Leg
https://max-everyday.com/2020/07/swei-b2-leg/
* 獅尾B2黑體 Swei B2 Sans
https://max-everyday.com/2020/07/swei-b2-sans/
* 獅尾腿圓 Swei Gothic Leg
https://max-everyday.com/2020/08/swei-gothic-leg/
* 獅尾彩虹腿 Swei Rainbow Leg
https://max-everyday.com/2020/08/swei-rainbow-leg/
* 獅尾XD珍珠 Swei XD Pearl
https://max-everyday.com/2020/07/swei-xd-pearl/
* 獅尾D露西 Swei D Lucy
https://max-everyday.com/2020/07/swei-d-lucy/
* 獅尾半月字體 Swei Gothic
https://max-everyday.com/2020/04/swei-half-moon/
* 台灣圓體 TaiwanPearl
https://max-everyday.com/2020/06/taiwanpearl/
* 獅尾圓體 Swei Gothic
https://max-everyday.com/2020/04/swei-gothic/
* 獅尾黑體 Swei Sans
https://max-everyday.com/2020/03/swei-sans/

獅尾宋體家族：
* 獅尾B2宋朝 Swei B2 Serif
https://max-everyday.com/2020/07/swei-b2-serif/
* 獅尾肉丸 Swei Meatball
https://max-everyday.com/2020/06/swei-meatball/
* 獅尾四季春字體 Swei Spring
https://max-everyday.com/2020/04/swei-spring/

其他字體：
* 何某手寫體 Nani Font
https://max-everyday.com/2020/09/nanifont/
* 內海字體  Naikai Font
https://max-everyday.com/2020/03/naikaifont/
* 莫大毛筆字體 Bakudai Font
https://max-everyday.com/2020/03/bakudaifont/
* 正風毛筆字體 Masa Font
https://max-everyday.com/2020/05/masafont/
* 假粉圓體 Fake Pearl 
https://max-everyday.com/2020/03/open-huninn-font/
* 俊羽圓體 Yu Pearl 
https://max-everyday.com/2020/03/yupearl/

其他網站：
* 清松手寫體 JasonHandWriting
https://jasonfonts.max-everyday.com/
* Max學習字體相關的筆記
https://codereview.max-everyday.com/font-readme/

## 贊助Max

很高興可以替中華民國美學盡一分心力、讓台灣擁有更好的文字風景，希望能提供另一種美學讓大家選擇，如果你覺得這篇文章寫的很好，想打賞Max，贊助方式如下：
https://max-everyday.com/about/#donate
