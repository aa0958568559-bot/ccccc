# 竹影日常

GitHub Pages 網站來源位於 repository root 的 `gh-pages/`。

## 部署

在 GitHub 儲存庫的 **Settings → Pages → Build and deployment**，選 **Deploy from a branch**，再選 branch `main` 和 folder `/gh-pages`，按 **Save**。

網站發布後，網址為 `https://aa0958568559-bot.github.io/ccccc/`。請把網域 `aa0958568559-bot.github.io` 加入 Firebase Authentication 的 Authorized domains，Google provider 需保持啟用。

Firebase client configuration lives in `gh-pages/firebase-config.js`; client config is public and must not contain service-account secrets. Protect Firebase data with Security Rules.





