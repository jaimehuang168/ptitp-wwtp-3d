# 部署到 GitHub Pages · Publicar en GitHub Pages

## 中文
1. 登入 https://github.com ，右上角「＋」→ **New repository**。
2. Repository name 填 `ptitp-wwtp-3d`，選 **Public**，其他不勾，按 **Create repository**。
3. 在新 repo 頁面點 **uploading an existing file**（或 Add file → Upload files）。
4. 打開本資料夾 `ptitp-wwtp-3d`，**全選裡面所有檔案與資料夾**（index.html、README.md、.nojekyll、docs、img），整批拖進上傳區。
   - 看不到 `.nojekyll`：檔案總管「檢視 → 顯示 → 隱藏的項目」打勾；漏掉也沒關係。
   - 一次最多 100 個檔案、單檔 25 MB，本網站 37 個檔案、最大 9 MB，可一次完成。
5. 等上傳進度跑完，下方按 **Commit changes**。
6. 到 **Settings → Pages**：Source 選 **Deploy from a branch**，Branch 選 **main**、資料夾 **/(root)**，按 **Save**。
7. 約 1–2 分鐘後網址生效：**https://jaimehuang168.github.io/ptitp-wwtp-3d/**
8. （建議）回到 repo 首頁，右側 About 齒輪 → Website 勾選「Use your GitHub Pages website」。

之後要更新：同樣 Add file → Upload files，上傳同名檔案即覆蓋，Pages 會自動重新發布。

## Español
1. Inicie sesión en https://github.com, clic en «＋» → **New repository**.
2. Nombre: `ptitp-wwtp-3d`, visibilidad **Public**, clic en **Create repository**.
3. En el repositorio nuevo, clic en **uploading an existing file** (o Add file → Upload files).
4. Abra esta carpeta `ptitp-wwtp-3d`, **seleccione todo su contenido** (index.html, README.md, .nojekyll, docs, img) y arrástrelo al área de carga.
   - Si no ve `.nojekyll`, active «Vista → Mostrar → Elementos ocultos»; no es imprescindible.
   - Límite: 100 archivos por carga y 25 MB por archivo; este sitio tiene 37 archivos (máx. 9 MB).
5. Cuando termine la carga, clic en **Commit changes**.
6. **Settings → Pages**: Source **Deploy from a branch**, Branch **main** y carpeta **/(root)**, clic en **Save**.
7. En 1–2 minutos estará disponible en: **https://jaimehuang168.github.io/ptitp-wwtp-3d/**
8. (Recomendado) En la página del repo, engranaje de «About» → marcar «Use your GitHub Pages website».

Para actualizar: Add file → Upload files con los archivos del mismo nombre; Pages se republica automáticamente.
