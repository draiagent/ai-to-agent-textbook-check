# AI to Agent Textbook Check

教材寫作與編輯檢查技能｜從學員痛點出發，讓內容前後連貫、白話易懂、能夠實作。

這套方法來自陳俊宏編寫《AI to Agent 課程教材》的改稿經驗：文字寫得多，不等於學員學得會。技能協助作者辨認讀者在哪裡跟不上，再做最小必要修改。

## 解決什麼問題

- 為湊固定頁數而重複內容。
- 從需求直接跳到操作，省略初學者需要的一步。
- 前後章用詞不同、案例突然換場。
- 標題提出痛點，正文卻只介紹名詞。
- 為了留下伏筆，硬塞下一章或沒有教完本章。

## 核心方法

先確認讀者起點與章節目的，再問六個問題：

**必要嗎？接得上嗎？看得懂嗎？問題解決了嗎？有回答標題嗎？前後一致嗎？**

以「痛點 → 原因 → 方法 → 示範 → 結果判斷」檢查邏輯，依原理章、實作章或總結章調整，不強迫每章同一格式。總綱是編輯依據，事實仍以來源查證；示例不代表實測成效。

## 使用

把 `skills/ai-to-agent-textbook-check/` 放入使用工具支援的技能目錄，或把 SKILL.md 和所需範本作為任務參考。實際載入方式依工具而定。

檢查：
> 請用 ai-to-agent-textbook-check 檢查第15章。讀者是已學會AI聊天的新手，先指出他會在哪裡跟不上，不改稿。

改寫：
> 請用 ai-to-agent-textbook-check 改寫這章，保留作者觀點，補上缺少的步驟，刪除重複，完成後自行檢查。

局部修正：
> 請將第二篇名稱統一為「任務設計」，檢查所提供檔案的相關位置，其他內容維持不變。

提供最新稿件、相關前後章與作者要求即可。沒有總綱時可用附帶範本整理已知資訊，不必為單句修改建立完整總綱。

## 專案結構

- `README.md`：本說明。
- `LICENSE`：沿用原始專案 CC BY-NC 4.0 授權。
- `skills/ai-to-agent-textbook-check/SKILL.md`：技能本體。
- `skills/ai-to-agent-textbook-check/agents/openai.yaml`：技能顯示資訊。
- `skills/ai-to-agent-textbook-check/assets/book-outline.md`：總綱範本。
- `skills/ai-to-agent-textbook-check/assets/revision-log.md`：修改前後紀錄。
- `skills/ai-to-agent-textbook-check/references/revision-examples.md`：白話表達與脈絡修訂示例。

## 檢查限制

技能提供編輯判斷，不能取代作者確認、專業事實查證與讀者實際試讀。未取得的章節不列為已檢查；不保證一次完成或固定效率提升。

## 作者與授權

陳俊宏｜https://github.com/draiagent

沿用原始專案的 CC BY-NC 4.0，授權全文：https://creativecommons.org/licenses/by-nc/4.0/ 。

AI Coach 益力康陳董 x CGM Coach 血糖教練  
2026 AI to Agent | 2027 AI to AGI Agent
