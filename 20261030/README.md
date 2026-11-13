# 竹影日常

GitHub Pages 網站來源位於 `docs/`。

## 部署

GitHub repository settings: **Pages → Build and deployment → Deploy from a branch → `main` / `docs`**。

網站發布後，請將 `<owner>.github.io` 加入 Firebase Authentication 的 Authorized domains，Google provider 需保持啟用。

Firebase client configuration lives in `docs/firebase-config.js`; client config is public and must not contain service-account secrets. Protect Firebase data with Security Rules.
