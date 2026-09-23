# KV AI Playbook — 獨立部署版

原本是 Claude Artifact（`https://claude.ai/artifact/G6Ukvs6LDSvupSMcyvAWx8`），2026-09-22 起另外建這個獨立 repo，目的是接 Vercel 部署成真正的網址，讓案例頁的「開 Agent」桌面版連結（`claude-cli://...`）能正常運作——Artifact 是沙盒環境，瀏覽器不允許裡面的內容觸發自訂協定開啟桌面 App，只有獨立網址才能用。

## 內容
- `index.html`：首頁
- `case-01.html` ~ `case-11.html`：11 套案例頁
- `wall.html`：案例牆
- `lab/`：兩套實作站教具（03、08）
- `assets/video/`：首頁背景影片素材

## 更新方式
Artifact 版本（給不需要桌面版連結的情境用）跟這個獨立 repo 版本是兩份平行維護的拷貝，之後改內容要兩邊都同步。正本工作檔在 `agents/web-design/projects/ai-kvalley-biz-site/site/`，改完那份再同步複製到這裡 push。

## 部署
接 Vercel：Vercel 後台 New Project → Import Git Repository → 選這個 repo → 不用額外設定，純靜態 HTML，直接 Deploy。
