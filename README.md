# AirClaim AI 展示包

這個資料夾是下周會議展示用的一套完整材料，主軸是把 AI、無紙化、效率導入行李理賠實際工作。

## 主要檔案

- `AirClaim_AI_會議展示.pptx`：新版會議簡報。
- `AirClaim_AI_Demo.html`：以根目錄 `AirClaim index.html` 原始碼為基礎擴充的離線系統展示。
- `data/airclaim_database.sqlite`：可查詢的 SQLite 資料庫。
- `data/airclaim_database.json`：HTML Demo 使用的完整資料。
- `data/schema.sql`：資料庫表格設計。
- `data/airclaim_cases.csv`：案件資料表，方便臨時匯入 Excel。
- `assets/airclaim_process_map.png`：AI + 無紙化工作流示意圖。
- `source/AirClaim index.original.html`：使用者提供的原始碼副本，方便追溯與後續開發。
- `content/會議展示重點.md`：展示時可照著走的重點稿。

## Demo 展示順序

1. 開啟 `AirClaim_AI_Demo.html`，先看原 AirClaim 介面延伸的總覽 KPI。
2. 進入「案件管理」，搜尋或點選 `TPE-2026-0147`。
3. 進入「新增案件」，輸入 World Tracer ID `TPECA18923`，示範自動帶入旅客、航班、航線與行李牌。
4. 進入「AI 智慧審查」，看主管摘要、缺件、照片鑑真、理賠上限提示。
5. 進入「文件管理」，看 Digital Vault 文件集中管理。
6. 進入「DATA 資料庫」，示範 JSON / CSV 匯出與資料表設計。

## 已實作功能

- 延續原始案件管理、建案、World Tracer、附件、財務結算、文件管理與報表。
- 新增 AI 智慧審查與 DATA 資料庫頁面。
- 新增案件會寫入瀏覽器本機資料；核准或退回會即時更新狀態與 KPI。
- 可匯出 JSON 完整資料庫與 CSV 案件資料。
- 全程離線使用，不需要外部字型或圖片連線。

> 資料皆為會議展示用模擬資料，未包含真實旅客個資。
