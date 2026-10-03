# Sigma Hacks Products

A free GitHub Pages APK download website.

## Put your APK online

1. Put your APK inside the `apks` folder.
2. Open `apps.js`.
3. Set the APK filename in `file`.
4. Commit/push the files to GitHub.
5. Enable GitHub Pages:
   - Repository → Settings
   - Pages
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`
6. Your permanent site address will be:
   `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

## Add more APKs

Add another object inside `const apps = [...]`:

{
  name: "Another App",
  description: "Description here",
  version: "1.0.0",
  size: "30 MB",
  file: "apks/AnotherApp.apk",
  icon: "assets/logo.png"
}

## Important

GitHub has file-size limits. For large APKs, use GitHub Releases and put the release asset URL in the `file` field instead of storing the APK directly in the repository.
