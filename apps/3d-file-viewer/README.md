# 3D File Viewer — v1.2.0

Open and explore 3D models on your phone.

- **APK:** [AminToor-3D-File-Viewer-v1.2.apk](AminToor-3D-File-Viewer-v1.2.apk)
- **Package:** `com.amintoor.viewer3d`
- **Version:** 1.2.0 (versionCode 3)
- **Main activity:** `com.amintoor.viewer3d.MainActivity`
- **Min. Android:** 8.0 (API 26) · **Target:** Android 15 (API 35)
- **Built with:** Android Gradle Plugin 8.13.2 · Three.js viewer (`GLTFLoader`)
- **Size:** 1,992,616 bytes (~1.9 MB)
- **SHA-256:** `7a25a6f4376f536c56f3df6fc463d5557e2a62d552de18a875c7d0aede096449`

## Supported formats (confirmed in app UI)

`STL · OBJ · PLY · 3MF · GLB · glTF`

File picker also accepts support/texture files: `.mtl, .bin, .png, .jpg, .jpeg, .webp`

## Features (confirmed in build)

- “Open and explore your models” library home
- File picker (“Open file”, “Could not open file picker” handling)
- Recent files + “See all”
- Search files
- Favorites tab
- Interactive 3D stage: “Drag to rotate”, model size chip, “Preparing model…” loading state
- Model position slider: Up / Down / Centered (`MODEL POSITION`)
- Share 3D model (“Share 3D model”, “Open the original file again to share it”)
- Settings tab, bottom navigation (Files / Favorites / Settings)

## Install

1. Download `AminToor-3D-File-Viewer-v1.2.apk`
2. Open it on Android 8.0+
3. Allow “Install unknown apps” if asked → Install
4. Use “Open file” and pick an STL/OBJ/PLY/3MF/GLB/glTF model

Verify: `sha256sum AminToor-3D-File-Viewer-v1.2.apk` must match the hash above.
