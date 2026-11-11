# 市集老闆的一天

像素風的小遊戲：60 秒內招呼客人、遞商品、收錢、補貨，看你能賺多少。
整個遊戲只有一個檔案 `index.html`，不需要安裝任何東西。

## 怎麼玩

1. 客人頭上會出現想買的商品。
2. 點下面的商品按鈕，遞給正在等的客人。
3. 客人頭上出現金幣，就點他收錢。連續收錢有加成。
4. 庫存快沒了按「補貨」。補貨的 1 秒多不能做別的事。
5. 客人等太久會走掉，連擊會中斷。

## 放到 GitHub 上（GitHub Pages）

介面名稱可能會有些不同，請以 GitHub 畫面為準。

1. 登入 GitHub，按右上角的「+」→「New repository」，名稱取 `market-game`，選 Public，按 Create。
2. 在新專案頁面點「uploading an existing file」，把 `index.html` 和 `README.md` 拖進去，按 Commit changes。
3. 到專案的 Settings → Pages，在 Source 選 `Deploy from a branch`，Branch 選 `main`，資料夾選 `/ (root)`，按 Save。
4. 等 1 到 2 分鐘，頁面上方會出現網址，通常是 `https://你的帳號.github.io/market-game/`，這個網址就可以貼到貼文。

## 想自己改的地方（都在 `index.html` 最上面的「可以自己改的設定」）

- `LINK`：貼上報名連結，遊戲結束時會出現按鈕。空白就不顯示。
- `T`：一天幾秒。
- `RANK`：營收達到多少算什麼稱號。這些數字是估計值，建議自己玩幾次再調整。
- `IT`：商品名稱與價格。
