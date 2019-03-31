---
title: 字型增補、網頁字型服務
date: 2018-09-09 09:09:07
cover_image: ji-hing.png
description: 字型增補、網頁字型服務
---

## 豆腐烏

支援本土語言漢字、羅馬字的烏體字型，修改自 [Source Han Sans](https://github.com/adobe-fonts/source-han-sans)。
若需要其他語言文字，會使佮 [Google Noto Fonts](https://www.google.com/get/noto/) 做伙使用。

- **[下載](https://github.com/tauhu-tw/tauhu-oo/raw/master/TauhuOo-Regular.otf)**
- [GitHub](https://github.com/tauhu-tw/tauhu-oo)
- 發佈日期
	- 2019-03-30
- 支援字符
	- Basic Latin (ASCII)
	- Big5-2003 漢字 (13,060 字)
	- 蘇州碼子（菁仔碼）
	- 全形 ASCII
	- 漢字、羅馬字標點符號
	- 表意文字描述字符
	- [本土語言外字表](/gua-ji-pio/)
		- 「⿸疒哥」採用萌典暫編碼「󿗧 (U+FF5E7)」
		- 「⿰車藏」採用全字庫暫編碼「󸾯 (U+F8FAF)」
		- 「⿺皮卜」採用萌典暫編碼「󿕅 (U+FF545)」
- 授權條款
	- [SIL Open Font License 1.1](https://scripts.sil.org/OFL)

## <div class=mootng>Tāu-hū Môo-tn̄g</div>

支援本土語言羅馬字的等寬字型，修改自 [Babelstone Modern](http://www.babelstone.co.uk/Fonts/Download/BabelStoneModern.ttf)。

- **[下載](https://github.com/tauhu-tw/tauhu-mootng/raw/master/TauhuMootng-Regular.otf)**
- [GitHub](https://github.com/tauhu-tw/tauhu-mootng)
- 發佈日期
	- 2019-03-30
- 支援字符
	- Basic Latin (ASCII)
	- 羅馬字標點符號
	- [本土語言外字表](/gua-ji-pio/)羅馬字部份
- 授權條款
	- [SIL Open Font License 1.1](https://scripts.sil.org/OFL)

<br>

## 網頁字型服務紹介
網站經過設定了後，就會當予網站內面的本土語言用字正常顯示。
提供 `.woff2`、`.woff`、`.otf` 三種格式，支援大多數的瀏覽器。
（注意：需要佇「會使家己設定 HTML、CSS」的網站才通使用。）

## 網頁字型服務使用步驟

### 一、種字型：

- 方法A、共這逝囥入去 HTML 的 `<head>` （推薦）
	- 豆腐烏
		- `<link href="https://tauhu.tw/tauhu-oo.css" rel="stylesheet">`
	- <div class=mootng> Tāu-hū Môo-tn̄g </div>
		- `<link href="https://tauhu.tw/tauhu-mootng.css" rel="stylesheet">`
- 方法B、共這逝囥入去 CSS 的上頭前
	- 豆腐烏
		- ` @import url(https://tauhu.tw/tauhu-oo.css); `
	- <div class=mootng> Tāu-hū Môo-tn̄g </div>
		- ` @import url(https://tauhu.tw/tauhu-mootng.css); `

### 二、指定字型：

- 透過編輯 CSS 的 `font-family` 來指定字型，推薦範例：
	- 豆腐烏
		- `font-family: tauhu-oo, PingFangTC-Regular, "Microsoft JhengHei", sans-serif;`
	- <div class=mootng> Tāu-hū Môo-tn̄g </div>
		- `font-family: tauhu-mootng, monospace;`