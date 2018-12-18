## 目標
這是拿來學習 firebase, serviceWorker, pushAPI, notificationAPI, localStorage, firebaseStorage 的專案

## 預計功能
1. 使用者設定提醒功能，設定1.日期以及2.項目名稱
2. 時間到了會跳出 notification 提醒使用者


## 預計使用技術
### 資料儲存
資料放在 firebase 上，App 開啟時取得資料
Bonus: 同步存一份在 localstorage ，離線時用 localstorage ，有網路時再同步至 firebase

### PushNotification
用瀏覽器提供的 push API 向 firebase 發出訂閱，收到 push 後用 Notification API 推播至手機(待研究)
Firebase cronjob 檢查提醒項目


## 其他
想做這個是因為一直想做冰箱剩餘食材相關的 App，如果沒有提醒功能的話那個 App 就相當於廢了一半了，所以先做這個練練手，順便熟悉大家都在用的 firebase。
