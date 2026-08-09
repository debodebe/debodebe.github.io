# 🌐 Debodebe Public Web (GitHub Pages)

Este repositorio contiene la configuración pública de **Android App Links** y la página receptora de enlaces compartidos para la app **Debodebe**.

## 📌 Configuración en GitHub:

1. Crea un repositorio público en tu cuenta de GitHub con el nombre `public-debodebe-app` (o `debodebe-app`).
2. Sube estos archivos a tu repositorio público:
   ```bash
   git init
   git add .
   git commit -m "Initial commit for GitHub Pages App Links"
   git remote add origin git@github.com:mafdes/public-debodebe-app.git
   git push -u origin main
   ```
3. Ve a tu repositorio en GitHub -> **Settings** -> **Pages**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` / `/ (root)`
   - Haz clic en **Save**.

4. Actualiza la huella **SHA-256** en el archivo `.well-known/assetlinks.json` con la huella digital de tu clave release (o de Google Play Console).
