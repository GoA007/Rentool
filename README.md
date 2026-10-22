# Rentool — Android 11 compatibility work

This repository is being prepared for an Android 11 (API 30) compatibility patch for Rentool, a Ren'Py RPA/RPYC archive toolkit.

## Status

The patched source archive is being staged for import. This initial commit does not yet contain the complete application source or the bundled FFmpeg-Kit AAR, so it is not buildable yet.

## Planned patch

- Lower the Android minimum SDK to API 30 (Android 11).
- Preserve the upstream project license and attribution when importing the complete source.
- Add a GitHub Actions workflow to build a debug APK.

Do not treat this repository as a release or a working APK until the full source is committed and the workflow succeeds.
