# HW1-1 實作過程紀錄 (Chat Log)

**User** (2026-03-11):
> HW1-1: 網格地圖開發
> 目標：開發一個大小為 nxn 的網格地圖，允許用戶指定維度 'n'（範圍從 5 到9），使用 Flask 網頁應用程式。
> 功能要求：
> 
> 用戶可以透過滑鼠點擊指定起始單元格（點擊後顯示為綠色）和結束單元格（點擊後顯示為紅色）。
> 用戶可以設定 n-2 個障礙物，透過滑鼠點擊將這些單元格變為灰色。

**Assistant**:
> 實作並將結果推送到 GitHub...
> 
> 專案結構
> 1. `app.py`：Flask 後端應用程式。
> 2. `templates/index.html`：前端網頁，包含 HTML, CSS, JavaScript。
>
> 過程：
> 透過 git clone 取得您的 Repo (`https://github.com/dds852456tw/DRL_HW1-1.git`)，利用 Flask 撰寫應用程式 `app.py`。
> 在前端 (`templates/index.html`)，依據要求實作以下功能：
> - 建立輸入框供使用者輸入介於 5 到 9 之間的維度 n，並依此動態產生 n x n 的網格。
> - 利用 JavaScript 綁定點擊事件，針對每個格子的點擊執行順序：起點 (綠色) -> 終點 (紅色) -> 障礙物 (灰色)，並設計上限最多為 n-2 個障礙物。
> 
> 最後使用 Git 指令將完成的程式碼進行 commit，並順利推到遠端儲存庫的 main 分支。

**User**:
> 接下來繼續做HW1-2
> ...

**User**:
> DRL_HW1-1 
> DRL_HW1-2
> 請將這些實作的紀錄各自存歷史紀錄

**Assistant**:
> (之前誤將檔名存為 `IMPLEMENTATION.md`，現依您的要求改為 `CHAT_LOG.md` 紀錄我們的操作流程。)
