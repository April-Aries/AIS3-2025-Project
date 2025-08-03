# AIS3 2025 新型態資安實務暑期課程 — 我只是餓了，怎麼變成 prompt injection 攻防戰？

> AI2 新竹旅遊智能客服 prompt injection 攻防戰

本專案為 AIS3 新型態暑期資安實務課程之課程專案，旨在透過 Flowise 平台建構具備防禦能力的智能客服代理人（Agent）。專案內容涵蓋意圖辨識、資訊摘要、系統規範與回覆提示設計，並可直接匯入 Flowise 進行部署與模擬。

## 🔧 專案檔案說明

| 檔名 | 類型 | 說明 |
|-------------------|--------------|----------------------------------------------------------------------|
| `Agentflow.json` | Flowise 架構檔 | 可直接匯入 Flowise 作為 Agent Flow 設計基礎。 |
| `Chatflow.json` | Flowise 架構檔 | 可直接匯入 Flowise 作為 Chat Flow 設計基礎。 |
| `IntensionTell.md`| Prompt 檔案 | 用於辨識使用者輸入意圖（如是否為有效查詢或含攻擊意圖）。 |
| `Response.md` | Prompt 檔案 | 智能客服的回覆邏輯與語調設計。 |
| `Summary.md` | Prompt 檔案 | 用於提取使用者輸入中的關鍵資訊並進行摘要。 |
| `SystemPrompt.md` | Prompt 檔案 | 定義整體系統的行為規範與限制，例如僅提供特定主題資訊。 |

## 🚀 快速開始

1. 開啟 [Flowise](https://cloud.flowiseai.com/)
2. 匯入 `Agentflow.json` 與 `Chatflow.json` 以載入完整架構
3. 檢視與修改各 Prompt 檔案內容（可透過 Flowise 中的 Prompt 節點匯入）
4. 測試與調整 Agent 行為以達到預期的資安防禦效果
