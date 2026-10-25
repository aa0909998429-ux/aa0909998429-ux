# Hi, I'm Kuan-Wei (Eric) Peng 👋

Computer Science student at Chang Gung University interested in distributed systems, data analysis, and practical software engineering.

## 個人專案

| 專案 | 專案特色與技術重點 |
|---|---|
| [Smart Medicine Cabinet](https://github.com/aa0909998429-ux/Smart_Medicine_Cabinet) | 使用 Flutter 建置智慧藥櫃原型，整合中／日文 OCR、SQLite 本機藥品搜尋、庫存追蹤、症狀篩選與重複有效成分提醒。 |
| [Distributed Wikipedia TF-IDF](https://github.com/aa0909998429-ux/distributed-wikipedia-tfidf) | 以 Docker Compose 建置分散式 Wikipedia 爬蟲，搭配 PHP 儀表板、3 個 Python Worker、Jieba 中文斷詞與 TF-IDF 關鍵字分析。 |
| [Future Crossroads](https://github.com/aa0909998429-ux/future-crossroads) | 互動式未來情境模擬網站：比較不同選擇的可能結果、代價與下一步。 |
| [Stock Prediction Dashboard](https://github.com/aa0909998429-ux/Stock-Prediction-Dashboard) | 使用 Python、Flask 與 Shioaji API 建立台股分析儀表板，整合市場資料、技術指標、機器學習預測及投資組合視覺化。 |
| [Smart Weight Scale](https://github.com/aa0909998429-ux/Smart_Weight_Scale) | 使用 Python 與 Bleak 連接 BLE 智慧體重計，透過預先掃描、快速握手、自動重試與 Nordic UART 解析即時體重資料。 |

## 團隊專案

| 專案 | 專案特色與技術重點 | 團隊 |
|---|---|---|
| [Taiwan PII Filter](https://github.com/JustinGNPS/tw-pii-filter) | 在資料送往雲端 AI 前，於本機偵測並去識別化臺灣常見個資；結合檢核碼驗證、NER 語意偵測、風險評分與可逆還原機制。 | 4 人 · [我的貢獻](https://github.com/JustinGNPS/tw-pii-filter/commits?author=aa0909998429-ux) |
| [PolicyVault Sentinel](https://github.com/MrJ6000/god_damn_chill_out) | 企業應付帳款的 AI 安全授權原型；以 Next.js、React、Express、TypeScript、Solidity 與 Foundry 分離 AI 付款提案、確定性政策與鏈上合約檢查。 | 5 人 · [我的貢獻](https://github.com/MrJ6000/god_damn_chill_out/commits?author=aa0909998429-ux) |
| Sarcopenia Skeletal Detection 🔒 | 結合凱比機器人與骨架分析的肌少症初步風險篩檢系統（非醫療診斷）：凱比負責語音引導與結果呈現，電腦端以 C922 錄影、MediaPipe 擷取骨架，並以 ST-GCN／Shift-GCN 等模型推論起立坐下、行走、半蹲三項動作。 | 4 人＋指導教授 · 我負責系統整合、凱比互動、語音辨識與競賽文件 · 含醫療個案資料，repo 不公開 |

<details>
<summary><b>Sarcopenia Skeletal Detection：我負責的工作</b></summary>

- **系統整合**：規劃「凱比負責互動、電腦負責分析」的雙端架構，把組員完成的模型、伺服器與介面串成可實際操作的檢測流程；實作並測試 USB 本機轉接與 Wi-Fi 兩種連線方式，以 Git 分支管理整合版本。
- **自動化互動流程**：啟動 → C922 確認受測者完整入鏡 → 凱比詢問姓名 → 語音辨識比對 Excel 名冊並帶入基本資料 → 本人確認 → 依序引導三項動作 → 上傳影片、分析並顯示結果。
- **語音辨識**：導入離線 Whisper 中文辨識，以名冊姓名與別名作為辨識提示；修正 Whisper 與 PyAV 版本不相容問題；處理凱比語音被 C922 麥克風收回的回音問題（播放結束後才收音、辨識時暫停提示音、回音過濾）。凱比內建麥克風收音已完成程式整合與單元測試，完整實機流程仍在驗證中。
- **硬體與實機測試**：凱比 ADB／USB 偵錯與反向連線、C922 影像與麥克風驗證、攝影機黑畫面與裝置辨識排除、人物入鏡與拍攝距離調整。
- **競賽與研究文件**：撰寫競賽企畫書、產品介紹、市場與競品分析（含 PoseFit 比較）、SDGs 對應、簡報與進度報告；明確區分已完成、待驗證與未來規劃。

</details>

## Skills

**Languages:** Python · TypeScript · JavaScript · PHP · Dart · Solidity
**Frameworks & Tools:** Flutter · Flask · Next.js · React · Express · Foundry · Docker · MediaPipe · Whisper · ADB · Git/GitHub
**Domains:** System Integration · Distributed Systems · Web Crawling · Data Analysis · NLP (TF-IDF, Jieba, NER) · Speech Recognition · BLE

## Contact

- Email: [aa0909998429@gmail.com](mailto:aa0909998429@gmail.com)
