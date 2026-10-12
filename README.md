CONTENTS
- index.html: complete self-contained game, including the supplied reference images.
- build-windows.bat: builds Windows installer and portable EXE.
- build-linux.sh: builds Linux AppImage and .deb packages on Linux.
- update-windows.bat / update-linux.sh: installs an updated HTML game into the app's update folder.
- main.js / package.json: Electron desktop wrapper and build settings.

WINDOWS
1. Install Node.js LTS from https://nodejs.org/
2. Extract this folder.
3. Double-click build-windows.bat.
4. After a successful build, look in dist for:
   Life-of-Nate-4.X-Setup.exe
   Life-of-Nate-4.X-Portable.exe

LINUX
1. Install Node.js LTS and npm.
2. Make the script executable: chmod +x build-linux.sh
3. Run ./build-linux.sh
4. The dist folder contains an AppImage and/or .deb package.
