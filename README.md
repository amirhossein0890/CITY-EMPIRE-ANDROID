# City Empire Android

Android WebView wrapper for the optimized City Empire HTML game.

## Build on GitHub
1. Upload the contents of this folder to the root of a GitHub repository on the `main` branch.
2. Open the repository's **Actions** tab.
3. Select **Build City Empire APK** and run it with **Run workflow**, or push a commit to `main`.
4. When the run finishes successfully, open the run and download the `City-Empire-APK` artifact.
5. Extract the artifact ZIP to get `app-debug.apk`.

The game is bundled locally in `app/src/main/assets/index.html`. Its external font stylesheet may still use internet access; gameplay itself is packaged in the app.
