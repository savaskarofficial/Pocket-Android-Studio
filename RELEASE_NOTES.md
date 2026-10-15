# Pocket Android Studio 0.2.10

- Automatically provisions a verified full ARM64 JDK 25 and registers it for Gradle discovery.
- Preserves project Java requirements and reuses matching installed JDKs and verified downloads.
- Removes the Java 21 downgrade repair button.

The previously observed Foojay HTTP 400 reported an unresolved package ID. Local matching-JDK provisioning addresses that download path; successful sync and builds remain project/device dependent. Previous device logs showed installed JDK 25, but used Java 21 daemon criteria and did not establish Java 25 daemon selection.

Download the APK in Assets. SHA256SUMS.txt provides its checksum. This release uses the supplied signed APK. Its signer differs from the previously supplied APK; an in-place update requires an installed copy signed by this same certificate. Export projects before replacing an incompatible installation.

Known limits: emulator unavailable, upstream Studio updates require a matching ARM64 profile, filesystem watcher restrictions and layout-preview warnings may remain. See README.md.
