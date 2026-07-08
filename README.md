# 婚禮座位安排

這是一個可直接部署到 GitHub Pages 的靜態互動式網頁。

## 使用方式

1. 將 `index.html` 放到 GitHub repository 根目錄。
2. 到 repository 的 Settings > Pages。
3. Source 選 `Deploy from a branch`，branch 選 `main`，資料夾選 `/root`。
4. 開啟 GitHub Pages 網址後即可拖曳名牌安排座位。

## 功能

- 14 桌座位安排
- 名牌拖曳到桌次或拖回待安排區
- 搜尋與來源、分類篩選
- 每桌容量調整
- 自動儲存在瀏覽器
- 匯出 / 匯入 JSON 備份
- 列印或存成 PDF

目前名單以 136 人建立，包含可能增加、可能不來、嬰兒與同行者。主桌容量為 12 人，其餘桌次預設為每桌 10 人。

## 共同編輯

目前這版是純 GitHub Pages 靜態版，資料只存在各自瀏覽器，因此兩個人同時開啟時不會即時看到對方變更。若要即時同步，需要再接 Firebase、Supabase 或其他線上資料庫；短期可以用匯出 / 匯入 JSON 交換安排結果。
