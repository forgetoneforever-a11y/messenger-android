# ZoVnilka

Android WebView wrapper for the ZoVnilka HTML prototype.

## Build APK

1. Open the **Actions** tab in this repository.
2. Select **Build ZoVnilka APK**.
3. Press **Run workflow** (or wait for a build after a push to `main`).
4. Open the completed run and download the `ZoVnilka-debug-apk` artifact.

The workflow copies the root `index.html` into the Android assets folder and builds a debug APK with Gradle.

## Current limitations

This repository currently contains a front-end demonstration. Chats, contacts, attachments, calls, accounts, and message delivery are not connected to a server. Messages are held in page memory and are not synchronized between devices. A real multi-user messenger requires a backend, authentication, a database, and secure real-time messaging.
