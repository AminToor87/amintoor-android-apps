# AminToor Converter — v1.1.0

PDF & document toolkit: merge, split, PPTX→PDF, images→PDF.

- **APK:** [AminToor-Converter-v1.1.apk](AminToor-Converter-v1.1.apk)
- **Package:** `com.amintoor.converter`
- **Version:** 1.1.0 (versionCode 2)
- **Main activity:** `com.amintoor.converter.MainActivity`
- **Min. Android:** 8.0 (API 26) · **Target:** Android 15 (API 35)
- **Built with:** Android Gradle Plugin 8.13.2
- **Size:** 10,332,970 bytes (~9.85 MB)
- **SHA-256:** `5656224682b2572cfcc87865cf47551859f6aa10c9be75d0844d019fde5c7f30`

## Features (confirmed in build)

- Merge PDFs (`MergeDocuments`, `PDFMergerUtility`, AcroForm/Document merge modes)
- Split PDFs (`SplitAtPage`, page-order validation)
- PPTX → PDF (`PdfFromPptx`, “This converter supports .pptx files”)
- Images → PDF (creates `AminToor_Images.pdf`; “Choose at least one image first”, “Choose a folder for the page images”)
- Open & save PDFs (`CurrentPdfUri`, `Edited.pdf`, “Could not open this PDF / document” handling)
- Page navigation (page up/down/left/right, current page tracking)
- Document file access via Storage Access Framework (`DocumentsContract`, `CREATE_DOCUMENT`, `OPEN_DOCUMENT`)

PDF engine: PDFBox (Tom Roush Android port) + BouncyCastle security provider.

## Install

1. Download `AminToor-Converter-v1.1.apk`
2. Open it on Android 8.0+
3. Allow “Install unknown apps” if asked → Install
4. Grant file access when opening/saving documents

Verify: `sha256sum AminToor-Converter-v1.1.apk` must match the hash above.
