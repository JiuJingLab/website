# 揪鏡 JiuJing｜Landing page

正式網址：https://jiujinglab.github.io/website/

純 HTML / CSS，無前端套件、追蹤器或外部字型；測試申請使用外連 Google Forms。GitHub Pages 從 `main` 根目錄部署。首頁以 HTML / CSS 功能示意呈現探索裝置、理解線索與相機人工確認；不是實際掃描結果。

本機預覽：

```bash
python3 -m http.server 8770 --bind 127.0.0.1
```

- App 原始碼：https://github.com/JiuJingLab/ios
- 獨立文件 repo：https://github.com/JiuJingLab/docs
- 隱私政策：https://jiujinglab.github.io/docs/privacy/
- 使用支援：https://jiujinglab.github.io/docs/support/

目前測試按鈕連至志願申請表，並清楚說明分批邀請。TestFlight 公開連結開放後，再更新 `#release-status` 及測試按鈕。不得把尚未審核的 build 描述成任何人皆可安裝，也不得宣稱掃描能保證找出或排除攝影機。

## 驗證紀錄（2026-09-29）

- 1280 px 桌面及 390 px 手機版視覺檢查通過。
- 手機版 scrollWidth = viewport width = 390，未見水平溢出。
- 全部圖片載入成功，FAQ 可展開，HTML 本機資產／連結檢查通過。
- 無 JavaScript、追蹤 SDK 或外部字型依賴。
- TestFlight 連結待實際上傳／Apple 處理完成後才加入。

2026-09-30：同步 v0.1 核定 Logo 與最新 Simulator 首頁截圖（`TestFlightFinal.xcresult`）；建置 0.1.0 (1) 已完成 Apple 處理並開放內部測試，公開測試連結仍待開放。

2026-09-30 v0.2：更新結果總覽截圖（明確標示模擬資料）、相機人工檢查能力與限制、相機權限及隱私說明。自動 MAC、全部 SSID 掃描與音訊偵測未實作。

v0.2 發佈驗證：`0.2.0 (2)` 已完成 Apple 處理並開放內部測試；官網 1280px 視覺檢查、圖片載入與 HTML 本機連結檢查通過，頁面未水平溢出。公開測試連結尚未開放。

## 志願測試招募（2026-09-30）

- 公開申請表：https://docs.google.com/forms/d/e/1FAIpQLSdzdQjYGL6-Jmyyk6onOKuoExmuiD8OD0J5rv0c4Ipi3wgdlA/viewform
- 首頁與頁尾招募區連至相同表單；導覽「申請測試」連至 `#try`。
- 6 題：暱稱、Email、裝置與系統版本、測試項目、使用情境（選填）、測試與資料使用確認。Email 有格式驗證。
- 任何知道連結的人都能填寫，無須 Google 登入；不限制單次回覆；不公開回覆摘要。
- 僅收集測試招募、邀請及回饋所需資料，不要求密碼、精確地址或檔案。資料儲存在 Google Forms，由擁有者在 Google Forms 管理回覆。
- 志願者是 TestFlight 外部測試者；依 Apple 審核及版本進度邀請，不授予 App Store Connect 團隊權限。填表不代表立即取得安裝連結。
- 不將 Google Form 編輯連結或作答資料放進公開 repo。

招募頁驗證：1280px 桌面、390px 手機首屏與招募區視覺檢查通過；320px、390px、1280px 無水平溢出。所有圖片正常，頁面錨點與本機資產檢查通過，按鈕能開啟公開表單。未登入表單可作答，5 題必填、1 題選填；Email 錯誤格式提示已驗證，未提交測試資料。
