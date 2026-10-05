# stockcalendar-catalog

公開稅表目錄，供 **股帳曆 / StockCalendar** App 讀取台灣綜合所得稅級距與相關常數。  
Public tax-table catalog for 股帳曆 / StockCalendar — not the app source code.

## Files

- [`tw_tax_tables.json`](./tw_tax_tables.json) — Taiwan income-tax brackets, deductions, and NHI supplementary premium constants by tax year (ROC years 113–115).

Raw URL used by the app:

```
https://raw.githubusercontent.com/jimmy77733/stockcalendar-catalog/main/tw_tax_tables.json
```

## Updates

財政部每年約 11–12 月公告下一年度免稅額、扣除額與級距後，請更新本檔的 `version` 與對應年度資料。  
Update this JSON (and bump `version`) when the Ministry of Finance announces new annual brackets — no App Store release required.

本目錄不含 App 原始碼。This repo does not contain the application source.
