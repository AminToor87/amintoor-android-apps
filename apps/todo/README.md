# AminToor To-Do

A lightweight task manager with quick voice entry for Hindi, Hinglish, and English commands.

- **APK:** [AminToor-To-Do.apk](AminToor-To-Do.apk)
- **Version:** 1.1.0 (versionCode 2)
- **Package:** `com.amintoortodo.app`
- **Main activity:** `com.amintoortodo.app.MainActivity`
- **Android:** 6.0+ (API 23), target Android 12L (API 32)
- **Size:** 33,601 bytes (~33 KB)
- **SHA-256:** `bc0b56112728f7fd4dcbad61519829497ec4a2a7e5c752f87b632f2e0b01dd0e`

## Features

- Add, edit, complete, and delete tasks; add an optional note.
- Set due dates, search tasks, and filter the list.
- Tap the microphone button and speak a task. The app extracts a title, date, and priority from supported Hindi/Hinglish and English phrases, then saves the task to the existing list.
- Examples: “27 तारीख को हाई प्रायोरिटी डॉक्टर से अपॉइंटमेंट लेना है” and “November 27, high priority, submit the report.” A day without a month (such as “27 तारीख”) means the next upcoming 27th. The parser also recognizes month names, numeric `DD/MM` dates, today, and tomorrow. If no priority is stated, the task is Medium.
- Voice-created tasks stay editable and are stored with other tasks on-device in `SharedPreferences`.

## Microphone and speech recognition

The app asks for microphone permission only after you tap the microphone button. Recognition uses the Android speech-recognition service available on the device, with Hindi (`hi-IN`) as the preferred language. Availability and whether recognition is processed on-device or by a service/network depend on the installed recognizer and device settings. AminToor To-Do does not save audio recordings or voice transcripts; it saves the parsed task fields.

## Install or update

1. Download `AminToor-To-Do.apk` and open it on Android 6.0 or newer.
2. Allow “Install unknown apps” if Android asks, then tap **Install**.
3. If updating an existing AminToor To-Do installation, the same package and release signing key are used; Android should retain the app's locally stored tasks.
4. Grant microphone access only if you want to add tasks by voice.

Verify the file with:

```sh
sha256sum AminToor-To-Do.apk
```

The result must match the SHA-256 value above.
