# Zeezap Business Manager (Android)

Native Android shell around https://aztersting.netlify.app.

- Opens the web app full screen in a WebView (JavaScript, local storage and cookies on)
- Pull down to refresh, back button goes back in the app
- Links to other sites open in the browser
- File upload and download supported
- Shows an offline screen with Retry when there is no internet

## Build the APK

1. Push this folder to a GitHub repo (branch `main`).
2. Open the **Actions** tab, run **Build APK** (it also runs on every push).
3. Download the `ZeezapBusinessManager-debug` artifact and install `app-debug.apk`.

## Change the website address

Edit `appUrl` in `app/src/main/java/com/azprime/zeezap/MainActivity.kt`
and the Retry link in `app/src/main/assets/offline.html`.
