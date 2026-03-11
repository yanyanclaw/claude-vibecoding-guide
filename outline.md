# Claude Vibe Coding 指南：給軟體業 PM、設計師與非工程師的 AI 開發上手書

## 目標讀者
軟體業的 PM、設計師、QA、行銷，平常跟工程師協作但自己不寫 code。你知道什麼是 API、Git、部署，但從沒自己動手做過。

## 核心命題
為什麼跟 AI 說了半天，它還是在那邊繞圈圈修不好？
因為你缺的不是更好的 AI，而是「怎麼跟 AI 協作」的方法論。

## 主力工具
Claude Artifacts（入門）→ Claude Code（進階）

---

## Part 1：AI 寫程式的時代來了

### 第一章：從 ChatGPT 到 AI 寫程式，一場靜悄悄的革命
- 2022：ChatGPT 橫空出世，你開始把程式問題丟給聊天機器人
- 2023：AI 狂熱 + AI 焦慮，台灣企業封鎖 AI，工程師也只當高級 Google 用
- 2024：Claude Artifacts、v0 出現，非工程師第一次「看到」成果
- 2025：AI Agent 崛起，Bolt.new、Lovable 爆發，非工程師成為主流使用者
- Vibe Coding 的定義與「原型自主權」

### 第二章：AI Agent vs 瀏覽器聊天 AI，搞懂你在跟誰說話
- 聊天 AI（ChatGPT、Gemini）：看不到你的檔案、改不了你的 code、記不住上下文
- AI Agent（Claude Code、Cursor、Bolt）：讀你的檔案、改你的 code、看到結果
- 中間地帶：Artifacts / v0（可預覽但只有前端）
- 本書路徑：Artifacts 入門 → Claude Code 進階
- 常見誤解：提示詞大補帖救不了你

### 第三章：認識矽谷 Vibe Coding 熱潮
- Andrej Karpathy 的那條推文：vibe coding 一詞的誕生
- 誰在用：r/vibecoding 63% 是非開發者
- Vibe Coding 能做什麼：MVP、內部工具、Landing Page、Dashboard
- Vibe Coding 不能做什麼：高安全性系統、高併發生產環境
- 現實 vs 期待：「說一句話就搞定」是個美麗的謊言

---

## Part 2：為什麼你會卡關

### 第四章：鬼擋牆的五種死法
- 死法一：需求模糊，你自己都不知道要什麼
- 死法二：一口吃成胖子，一個 prompt 塞進整個 app
- 死法三：錯誤描述不清，「它壞了」不是 bug report
- 死法四：沒有存檔點，改壞了回不去
- 死法五：不懂邊界，硬要 AI 做它做不到的事

---

## Part 3：破解卡關的核心技能

### 第五章：拆解力，把大象切成小塊
- 為什麼「幫我做一個電商網站」注定失敗
- 需求拆解框架：功能清單 → 優先排序 → 單一任務
- 實例：「我要一個 CRM」拆成 20 個可執行的小任務
- 每一步都要能驗證：Done 的定義

### 第六章：描述力，說 Claude 聽得懂的話
- AI 不是你同事，它沒有「常識」
- 好 prompt 的結構：角色、目標、限制、格式、範例
- 實戰對比：同一個需求，爛 prompt vs 好 prompt
- Claude 特有的溝通技巧：Artifacts 指令、Claude Code 的 CLAUDE.md

### 第七章：除錯力，卡住時怎麼自救
- 你不需要會修 code，但你需要會「描述症狀」
- 錯誤訊息是你的朋友：怎麼讀、怎麼貼給 Claude
- 截圖比文字有用：善用視覺化回報問題
- 知道什麼時候該砍掉重練，而不是繼續繞圈

### 第八章：版本控制，你的後悔藥
- 為什麼不存檔是 vibe coding 最大的坑
- 最低限度的 Git：init、add、commit（只要這三個）
- Claude Code 會幫你用 Git，但你要知道它在幹嘛
- 壞了就回滾：不用怕把事情搞砸

---

## Part 4：Claude 實戰

### 第九章：Claude Artifacts，十分鐘做出你的第一個原型
- 打開瀏覽器就能用，零安裝
- 實戰：從一句話到可互動的前端原型
- Artifacts 的能力邊界：能做什麼、不能做什麼
- 什麼時候該畢業，進入 Claude Code

### 第十章：Claude Code 環境設定，十五分鐘搞定
- 安裝 Node.js 和 Claude Code
- 終端機不可怕：你只需要會這五個指令
- 第一次跑起來：讓 Claude Code 幫你做一個小專案
- CLAUDE.md：教 Claude 認識你的專案

### 第十一章：用 Claude Code 做一個真的產品
- 從 Artifacts 原型升級成完整專案
- 前端 + 後端 + 資料庫，Claude Code 怎麼幫你搞定
- 部署上線：讓別人也能用你做的東西
- 常見踩坑與解法

---

## Part 5：你的角色怎麼用

### 第十二章：PM，不再只會畫 wireframe
- 痛點：需求寫了一堆，工程師說排不進去
- 解法：自己做可互動原型，用「看得到的東西」推動決策
- 實戰：從 PRD 到可點擊原型的完整流程
- 進階：自己做數據 dashboard，不再等 BI

### 第十三章：設計師，從 mockup 到會動的產品
- 痛點：設計稿丟給工程師，做出來差很多
- 解法：自己把設計變成 code，掌控每一個像素
- 實戰：Figma 設計稿 → Claude Code → 部署上線
- 進階：用 Claude 建立互動式設計系統

### 第十四章：其他角色，QA、行銷、業務
- QA：用 Claude Code 自動產生測試案例、寫自動化測試腳本
- 行銷：Landing page 一小時上線、自動化行銷流程
- 業務：內部報表工具、客戶 demo 快速產出

---

## Part 6：走得更遠

### 第十五章：知道自己的邊界
- Vibe Coding 能做到哪裡、不能做到哪裡
- Demo ≠ Production：安全性、效能、可維護性
- 與工程師協作的正確姿勢：交接而非對抗

### 第十六章：持續進化
- AI 工具每個月都在變，怎麼跟上
- 從 vibe coder 到 vibe architect
- 未來趨勢：Multi-agent、AI 原生開發流程

---

## 附錄
- A：Claude Artifacts vs Claude Code 功能對照表
- B：30 個實戰 Prompt 模板（Claude 專用）
- C：「鬼擋牆」急救錦囊
- D：術語表
