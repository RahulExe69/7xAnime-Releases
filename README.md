# 7xAnime Releases

Official Android release channel for **7xAnime**.

## Downloads

Open the [latest published release](https://github.com/RahulExe69/7xAnime-Releases/releases/latest) to download the current signed APK.

Each published release is intended to include:
- A versioned 7xAnime APK.
- A SHA-256 checksum file.
- Release notes, versionCode, and build metadata.

## Installation and updates

Install the APK from a published release. Android may ask you to allow installation from the source app and to confirm the package installation; those are Android security controls.

The Android app checks this repository's latest published release at startup. When a newer version is available, the app presents a required update screen. Temporary network/API failures do not block initial startup.

## Release integrity

Official releases are built by GitHub Actions in the private [7xAnime source repository](https://github.com/RahulExe69/7xAnime) and signed with the same persistent Android release keystore. The signing keystore and credentials are intentionally not stored in this public repository.

The checksum is useful for detecting accidental corruption during transfer. Android's package installer separately verifies the APK signature.
