# 揪鏡 JiuJing｜Landing page

正式網址：https://jiujinglab.github.io/website/

純 HTML / CSS，無前端套件、追蹤器、外部字型或表單。GitHub Pages 從 `main` 根目錄部署。App 畫面來自 iOS Simulator 的真實介面，不是硬體偵測效果展示。

本機預覽：

```bash
python3 -m http.server 8770 --bind 127.0.0.1
```

- App 原始碼：https://github.com/JiuJingLab/ios
- 獨立文件 repo：https://github.com/JiuJingLab/docs
- 隱私政策：https://jiujinglab.github.io/docs/privacy/
- 使用支援：https://jiujinglab.github.io/docs/support/

TestFlight 公開連結開放後，再更新 `#release-status` 及測試按鈕。不得把尚未審核的 build 描述成任何人皆可安裝，也不得宣稱掃描能保證找出或排除攝影機。

## 驗證紀錄（2026-09-29）

- 1280 px 桌面及 390 px 手機版視覺檢查通過。
- 手機版 scrollWidth = viewport width = 390，未見水平溢出。
- 全部圖片載入成功，FAQ 可展開，HTML 本機資產／連結檢查通過。
- 無 JavaScript、追蹤 SDK 或外部字型依賴。
- TestFlight 連結待實際上傳／Apple 處理完成後才加入。
