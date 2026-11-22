BIMA KIRANA - Android WebView app project

To generate a directly installable APK without installing Android Studio locally:
1. Create/sign into GitHub and create a new repository.
2. Upload the contents of this folder to the repository (branch main).
3. Open the repository's Actions tab and run/observe "Build Bima Kirana APK".
4. When the workflow succeeds, open the run and download the artifact named "Bima-Kirana-APK".
5. Extract the artifact ZIP; app-debug.apk is the installer. On Android, allow installing from the file manager if prompted.

The included GitHub Actions workflow builds app-debug.apk automatically on push to main or manually via Actions.

This ZIP is still a project source, not a precompiled APK. Building requires GitHub Actions or Android Studio.
