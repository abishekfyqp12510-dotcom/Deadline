# Schedule Submission Reminder (Android)

Reminds you when schedules of work are due for submission. Built with Capacitor, so the same web page runs as an Android app.

## Build the APK on GitHub
1. Upload all these files to the repository.
2. Open the **Actions** tab, choose **Build Android APK**, and tap **Run workflow**.
3. When it finishes, download the `schedule-reminder-apk` artifact and install `app-debug.apk`.

## Files
- `index.html` — the app
- `capacitor.config.json` — app name and ID
- `package.json` — dependencies
- `.github/workflows/build-apk.yml` — builds the APK in the cloud
