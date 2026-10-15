# Changelog

## Repository refresh — 2026-10-15

- Replaced the two earlier screenshots with five newly supplied, unmodified phone captures.
- Updated the README gallery to show projects, file browsing, Studio layout editor, touch shortcuts and diagnostics.
- Replaced the previous release asset with `PocketAndroidStudio-0.2.10_sign.apk`, exactly as supplied.
- Updated release-upload commands, SHA-256 checksum and signer compatibility notes.
- Confirmed all entries from the previous APK are byte-identical after decompression; this upload adds JAR signing files. This refresh does not patch application behavior or change its embedded version.

## App 0.2.10

- Provisions a full ARM64 JDK 25 for matching Gradle requirements, using verified downloads and reuse of installed matching JDKs.
- Preserves project Java criteria rather than applying the previous Java 21 downgrade workaround.
- Removes the downgrade repair button.

Device builds, Java daemon selection, runtime updates, filesystem watching and layout preview still require project/device validation. The supplied screenshots visibly retain filesystem-watcher warnings.
