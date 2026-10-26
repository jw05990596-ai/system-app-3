SYSTEM: DAILY QUEST (Android app project)

A real Android app (APK) with its own private storage, separate from any browser.
It works offline. Only photo scanning uses the internet: it opens Google Lens, you copy
the text it reads, and paste it into the app (no API key needed).

FIRST TIME: build the APK
1. Create a free GitHub account and a new private repository.
2. Put everything from this folder into the repository (GitHub Desktop is easiest;
   make sure the hidden .github folder is included).
3. Open the Actions tab. "Build APK" runs by itself (or press Run workflow). 5 to 10 minutes.
4. Open the finished run, download "system-apk", unzip, send app-debug.apk to your phone, install it.

UPDATING
Replace the changed files in the same repository (usually only www/index.html), commit and push.
Install the new APK OVER the old app (do not uninstall) and your data stays.
Settings > Data > Copy backup is a good habit before big updates.

THEMES AND ART
Settings > Theme: System, Sung Jin-Woo, Sekiro, Tarnished. Each theme has its own colours,
effects and level-up animation. Pick images from your own gallery for the background, the
hero portrait and each character that pops out. They are stored on your phone only.
