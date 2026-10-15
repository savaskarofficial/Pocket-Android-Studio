# Supplied APK verification

| Check | Result |
| --- | --- |
| File | `PocketAndroidStudio-0.2.10_sign.apk` |
| Bytes | 296870 |
| SHA-256 | `b106ba0714c0cd667be6cc3e5f5cd6177ac609006188fc13be9e79ad40fa62ae` |
| Package | `com.undercoveritfirm.studiopocket` |
| Version | 0.2.10 / code 16 |
| Android SDK | min 26; target 28; compile 35 |
| ZIP CRC | Passed |
| JAR signer cryptographic signature | Verified using OpenSSL CMS; certificate trust/identity is not independently attested |
| JAR signature → manifest → entry SHA-256 digests | Passed, including all non-META-INF payload entries |
| Payload comparison | All previous APK entries match byte-for-byte after decompression; new JAR signing metadata added |
| Signer certificate SHA-256 | `bca52ad2acd8031cdd0279c21a609e91d718eb8a88a6de59018b0f31484999e9` |
| Previous APK v2 signer certificate SHA-256 | `d848851318b1b98d3e1378da5cb6e873ca24c3632c6c2369e468a47b11798ff1` |
| Signer matches previous APK | No |

The supplied signed APK is copied unchanged. The checks above verify its archive/JAR signature chain and embedded metadata, not execution on a phone, APK v2/v3/v4 verification, installer acceptance or comprehensive application correctness. No rebuild was performed.

An installed APK signed by a different certificate cannot be updated in place with this one. Export projects before replacing an incompatible installation. Uninstalling removes private app data. Subsequent versions should use this release’s maintained signing identity; no private key is included in this package.

The five screenshot bytes match the new uploads. No earlier screenshots remain. The screenshots show Studio 2026.1.4.7 through the ARM64 runtime and visible filesystem-watcher warnings; they do not prove every future Studio release is compatible or that APK compilation completes.
