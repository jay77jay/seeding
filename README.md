# 播種配貨（手機）

EZFUN 倉庫散單播種用的手機頁。任務由整單系統 order-batcher 的「發布播種任務」建立（Firestore `seeding_tasks`），被指派的同事用 Google 登入後操作。

- 網址：https://jay77jay.github.io/seeding/
- 籃號：A 面 1～25、B 面 26～50，每面 5 層 × 5 格，從最上層左邊開始。
- `?demo=1`：假資料測試模式，不連資料庫。
- 版本字串在 `seeding.html` 的 `SEED_VERSION`。
