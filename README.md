# CornerCam: releases

This repository holds only the release files (Windows installer and SHA-256 checksum) of CornerCam, so that the program's built-in update check can download them. It contains no source code.

- Download the latest `SwissdentRtspViewer-<version>-x64.msi` from the [Releases](../../releases) page. The `.sha256` file next to it holds the checksum.
- The viewer checks for updates only when you choose "Frissítések keresése..." in its right-click menu.
- The installer ships unmodified LGPL builds of the FFmpeg shared libraries (BtbN FFmpeg-Builds, https://github.com/BtbN/FFmpeg-Builds; source: https://ffmpeg.org). The license files are installed next to the DLLs. You may replace the DLLs with your own compatible build.
