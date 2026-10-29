# Olkaria 3 TG Alignment (Android)

Offline Android app for rim-and-face DTI turbine-generator coupling alignment for the Olkaria III
units (generator = reference). Default dimensions are from OEC 42: D 476 mm, A 1500 mm,
B 2700 mm; edit them for the unit being aligned.

The calculator itself is `app/src/main/assets/index.html`. Edit that file to change the app.

## Get the APK without installing anything (GitHub, free)
1. Create a free account at github.com and make a new repository (e.g. `olkaria3-tg-alignment`).
2. On the repository page choose **Add file > Upload files**, drag in everything from this folder
   (including the hidden `.github` folder), and commit.
3. Open the **Actions** tab. The "Build APK" run starts by itself (or press **Run workflow**).
4. When it shows a green tick (about 3-5 minutes), open the run and download
   **Olkaria3-TG-Alignment-APK** at the bottom. Unzip it to get `app-debug.apk`.

## Or build in Android Studio
Open this folder in Android Studio, let it sync (it will set up Gradle), then
**Build > Build App Bundle(s) / APK(s) > Build APK(s)**.

## Install on the phone
Copy `app-debug.apk` to the phone, tap it, and allow "Install unknown apps" for your file
manager when Android asks. Android 8.0 or newer is required.
