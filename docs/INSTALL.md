# Install guide

All three apps install directly from APK — no Play Store needed.

## Steps (same for all apps)

1. Download the APK you want from this repo or the Releases page.
2. Open the file on your Android phone (from browser downloads or file manager).
3. Android will ask for **“Install unknown apps”** permission for that app (browser or file manager) — allow it once.
4. Tap **Install**, then **Open**.

## Requirements

| App | Minimum Android | File |
|-----|-----------------|------|
| AminToor To-Do | Android 6.0+ | `apps/todo/AminToor-To-Do.apk` |
| AminToor Converter | Android 8.0+ | `apps/converter/AminToor-Converter-v1.1.apk` |
| 3D File Viewer | Android 8.0+ | `apps/3d-file-viewer/AminToor-3D-File-Viewer-v1.2.apk` |

## Verify your download (recommended)

Compare the SHA-256 hash of your downloaded file with [CHECKSUMS.md](CHECKSUMS.md):

```sh
sha256sum AminToor-To-Do.apk
sha256sum AminToor-Converter-v1.1.apk
sha256sum AminToor-3D-File-Viewer-v1.2.apk
```

On Windows (PowerShell):

```powershell
Get-FileHash .\AminToor-To-Do.apk -Algorithm SHA256
Get-FileHash .\AminToor-Converter-v1.1.apk -Algorithm SHA256
Get-FileHash .\AminToor-3D-File-Viewer-v1.2.apk -Algorithm SHA256
```

## Troubleshooting

- **“App not installed”**: you may have an older conflicting signature — uninstall the old version first (back up tasks/files), then reinstall.
- **“Unknown apps” blocked**: Settings → Apps → Special app access → Install unknown apps → allow your browser/file manager.
- **Converter / Viewer can’t open a file**: grant file access when prompted, and make sure the file extension is supported (Converter: PDF/PPTX/images; Viewer: STL/OBJ/PLY/3MF/GLB/glTF).
