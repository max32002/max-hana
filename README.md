# Max的花園 Max Hana

分享花園明朝字體的相關改作字型。

## B2花園 (B2 Hana)
B2花園字體基於花園明朝的轉角的三角形轉成半圓形改造，彷彿墨暈或是稍微過曝的效果。歡迎大家自由應用、自由優化、自由改作！
![B2花園字體預覽](https://github.com/max32002/max-hana/raw/master/preview/welcome_b2hana.png)

B2花園與花園明朝字體比較：
![B2花園字體比較預覽](https://github.com/max32002/max-hana/raw/master/preview/compare_hana_b2.png)

附註：Regular 字重，是直接來自花園明朝，Medium 字重是透過程式產生，不能確定所有的字都正常，可能會轉換失敗。

## 花園肉丸 (Hana Meatball)
花園肉丸字體基於花園明朝的三角形換半圓形改造，遊走於古典與可愛之間的字體。歡迎大家自由應用、自由優化、自由改作！
![花園肉丸字體預覽](https://github.com/max32002/max-hana/raw/master/preview/welcome_hahameatball.png)

花園肉丸與花園明朝字體比較：
![花園肉丸字體比較預覽](https://github.com/max32002/max-hana/raw/master/preview/compare_hana_meatball.png)

附註：Regular 字重，是直接來自花園明朝，Medium 字重是透過程式產生，不能確定所有的字都正常，可能會轉換失敗。

三角形換半圓形改造
## 檔案說明
* HanaMinA.ttf 花園明朝字體A+G區。原版的花園明朝只有A區。
* HanaMinB.ttf 花園明朝字體B-F區。
* B2Hana-Regular.ttf B2花園 Regular 字重
* B2Hana-Regular.ttf B2花園 Medium 字重 (線條較粗)
* B2HanaB-Regular.ttf B2花園（B-F區） Regular 字重
* B2HanaB-Regular.ttf B2花園（B-F區） Medium 字重 (線條較粗)

附註1：一般情況下，使用 A區就可以了，常用字在A區，其他區的字比較少使用到。
附註2：為什麼要分成2個字型檔？因為單一字型檔有字數的上限，所以需要分成2個。

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」，或點進想下載的ttf字型檔案，再點「Download」的按鈕進行下載。

## 使用 WebFont

網路字型(Web Font)，用於網頁上的字型顯示，使用者的用戶端不需預先安裝字型檔，一樣能夠看到特殊的字型效果。實現該功能的原理是在瀏覽時才下載字型檔。

花園明朝可以服用下面的css:
```
@font-face {
  font-family: HanaMinA;
  src: url(https://github.com/max32002/max-hana/raw/master/webfont/HanaMinA.woff2) format("woff22")
  , url(https://github.com/max32002/max-hana/raw/master/webfont/HanaMinA.woff) format("woff");
}
```

B2花園Regular,可以服用下面的css:
```
@font-face {
  font-family: B2Hana-Regular;
  src: url(https://github.com/max32002/max-hana/raw/master/webfont/B2Hana-Regular.woff2) format("woff22")
  , url(https://github.com/max32002/max-hana/raw/master/webfont/B2Hana-Regular.woff) format("woff");
}
```
B2花園Medium,可以服用下面的css:
```
@font-face {
  font-family: B2Hana-Medium;
  src: url(https://github.com/max32002/max-hana/raw/master/webfont/B2Hana-Medium.woff2) format("woff22")
  , url(https://github.com/max32002/max-hana/raw/master/webfont/B2Hana-Medium.woff) format("woff");
}
```

您也可以透過從CDN引入在GitHub上woff2檔案的網址，再把上方的url()內容置換成CDN快取後的網址，將可大幅加快網頁載入。推薦使用 jsDelivr 的服務，在速度上挺不錯的，參考看看： www.cdnperf.com/#!performance,Asia 。

## 附註
* B2花園字體的演算黑科技，將字體轉角的三角形轉成半圓形，請參考獅尾B2宋朝專案下的 /python/ 目錄下的腳本檔案。透過調整程式碼，也許也可以產生出新的有趣字型。目前的程式應該還有很多錯誤或需要再加強的地方。請先把要處理的字型，轉成 FontForge 的 sfdir, 再透過程式去處理產生出來的檔案。

## 著作權與授權

* 本字型是改造グリフウィキ(GlyphWiki)所開發、發表的「[花園明朝(花園フォントについて)](http://fonts.jp/hanazono/)」字型。
* 本字型亦基於 SIL Open Font License 1.1 授權條款免費公開，關於授權合約的內容、免責事項等細節，請詳讀 License 文件。
    * 可自由商用 不需付費、知會或標明作者，即可自由使用此字型，亦可做商業應用。
    * 可自由傳布 可自由分享檔案、將檔案安裝於任何軟硬體中。
    * 可自由改作為其他字型 將字型檔案修改重製為其他字型檔案，改作後的字型檔案須同樣依 Open Font License 釋出。
    
    
## 相關網頁

* 花園肉丸
https://max-everyday.com/2020/08/hana-meatball/
* B2花園
https://max-everyday.com/2020/08/b2-hana-font/
* 獅尾B2宋朝 Swei B2 Serif
https://max-everyday.com/2020/07/swei-b2-serif/
* 獅尾肉丸 Swei Meatball
https://max-everyday.com/2020/06/swei-meatball/
* 獅尾四季春字體 Swei Spring
https://max-everyday.com/2020/04/swei-spring/
* 內海字體 (NaikaiFont) 
https://max-everyday.com/2020/03/naikaifont/
* 莫大毛筆字體 (Bakudai)
https://max-everyday.com/2020/03/bakudaifont/
* 正風毛筆字體 (MasaFont)
https://max-everyday.com/2020/05/masafont/
* 清松手寫體 (JasonHandWriting)
https://jasonfonts.max-everyday.com/

## 贊助Max

很高興可以替中華民國美學盡一分心力、讓台灣擁有更好的文字風景，希望能提供另一種美學讓大家選擇，如果你覺得這篇文章寫的很好，想打賞Max，贊助方式如下：
https://max-everyday.com/about/#donate
