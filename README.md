# Eat That Frog (Android)

Build the APK for free in the cloud:
1. Create a new GitHub repository and upload everything in this folder (keep the .github folder).
2. Open the repo's Actions tab, pick "Build Android APK", and press Run workflow (it also runs on every push).
3. When it turns green (about 4 minutes), open the run and download the "eat-that-frog-apk" artifact.
4. Unzip it, send app-debug.apk to your phone, and open it. Allow "install unknown apps" when asked.

To change the app, edit www/index.html and push again.

Reminders: the first time you switch them on, Android asks for notification permission. Allow it.
