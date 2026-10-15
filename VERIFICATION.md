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
