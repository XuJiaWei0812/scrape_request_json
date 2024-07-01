# scrape_request_json

這是一個使用 Python 爬取電影資料的專案，用於練習 requests 爬取動態網頁的方法。

## 功能介紹

- 從 `API` 獲取電影列表及詳細資訊
- 解析 `JSON` 數據
- 將數據寫入 `Excel` 檔案
- 防止重複數據
- 使用隨機User-Agent和延遲來避免被封鎖

## 使用套件

- `requests` : 用於發送 HTTP 請求
- `fake_useragent` : 生成隨機 User-Agent
- `openpyxl` : 操作 Excel 檔案

## 如何使用

1. 安裝必要的套件:
   
   ```bash
   pip install requests fake_useragent openpyxl
   ```
2. 運行腳本:
   
   ```bash
   python scrape_requests_json.py
   ```
3. 自動爬取網站的所有頁面，並將結果保存在 `scrape_reques_json.xlsx` 文件中。

## 注意事項

- 本爬蟲專案僅供學習和研究使用
- 請遵守網站的 `robots.txt` 規則和使用條款
