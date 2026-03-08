---
description: Prepare a new release for the Android app
---

This workflow automates the version bumping and changelog update for a release.

1. Bump `versionCode` and `versionName` in `android/app/build.gradle.kts`.
2. Update `CHANGELOG.md` with the new version and date.
3. Commit the changes (if in a git repo).
// turbo
4. Run `./gradlew assembleRelease` to verify the build.
