# 安全及家庭使用

這是公開的靜態網站，所以原始碼任何人都可以閱讀；V2 repository 內沒有密碼、API key、登入資料或私人家庭資料。ETA 只向九巴、城巴及港鐵的公開 HTTPS API 讀取資料。

收藏、主題及排序只保存在各自裝置的瀏覽器 `localStorage`，不會送到本 app 或其他家人的裝置。全家可以同時開啟同一個 [V2 網址](https://bugu-robot.github.io/bus-eta-app-v2/)，不需要登入或共用帳戶；每部手機會有自己的收藏。

GitHub Pages 使用 HTTPS；GitHub repository 的 Secret Protection 及 Push Protection 已啟用。API 服務繁忙時可能回傳暫時錯誤或 429，app 會保留上次顯示的 ETA。這個簡單版本沒有跨裝置同步功能；如日後需要共用收藏，必須另外加入後端或手動匯出／匯入功能。
