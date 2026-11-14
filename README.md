# Paizo Organized Play 頁面改善（繁／简）

把 paizo.com 的組織遊戲頁面（回報表單、角色列表、場次、GM／活動、福利）翻成中文並重新排版的 Tampermonkey 腳本，給台灣 PFS 分部的 GM 與玩家用。介面可以切換繁體／简体。

## 安裝

1. 瀏覽器裝 [Tampermonkey](https://www.tampermonkey.net/)。Chrome、Edge 還要打開擴充功能的「允許使用者腳本」開關（或開發人員模式），見 [Tampermonkey FAQ Q209](https://www.tampermonkey.net/faq.php?q=Q209)。
2. 點這個網址安裝：<https://raw.githubusercontent.com/quasiidem-lab/paizo-report/main/paizo-report.user.js>
3. 打開 [Paizo 組織遊戲帳號頁](https://paizo.com/organizedPlay/myAccount)，看到中文就裝好了。

從上面的網址安裝才會自動更新。以前下載檔案拖進瀏覽器安裝的，請從網址重裝一次。

圖文教學：<https://claude.ai/artifact/MA7mmsWnLkcPWLcmnFEboC>

## 說明

- 腳本只改畫面，不改表單送出的資料，也不會替你按送出。
- 劇本名與福利的中譯另外放在網路上讀取，譯文修正不用等腳本改版。
- 這個倉只放發布用的成品，每次出新版自動更新；版本說明見各次 commit。

本工具為社群製作的非官方工具，與 Paizo Inc. 無關。Pathfinder 與 Pathfinder Society 為 Paizo Inc. 的商標。
