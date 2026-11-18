<div align="center">

<img src="./banner.svg" alt="Matheus Maignardi - Mobile Engineer" width="100%" />

<a href="https://www.linkedin.com/in/matheus-maignardi/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:mmaignardi@hotmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
<img src="https://img.shields.io/badge/Brazil-009C3B?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Brazil" />

</div>

---

## 🧑‍💻 About me

- 📱 **5+ years** shipping native and cross-platform apps on Android, iOS and the web
- 🎙️ Currently building **Motorola's Audio Recorder** app (Instituto Eldorado)
- 💳 Previously worked on **Samsung Wallet** (SiDi), **Localiza** (iOS) and **Méliuz** (React Native)
- 🔐 Deep interest in **mobile security**: RASP, anti-tampering, obfuscation and hardware-backed crypto
- 🚀 Built **Alting Social** from zero to production on iOS, Android and Web as a side project
- 🎓 B.Sc. in Computer Science · Postgraduate studies in High-Performance Computing

---

## ⭐ Featured open source

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ [MaigShield](https://github.com/Maignardi/MaigShield)

Android **RASP & anti-fraud SDK** for banking and fintech apps.

- Zero-boolean design: the device never decides, the backend does
- 76-byte telemetry proof, RSA-OAEP + AES-256-GCM, signed with a **StrongBox/TEE** key
- Native **C++20** core with direct syscalls: Frida, Xposed, Magisk, root and hook detection
- Banking-trojan defenses: accessibility abuse, screen mirroring, tapjacking
- Behavioral biometrics (bot and duress scores)

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![C++20](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![NDK](https://img.shields.io/badge/Android_NDK-3DDC84?style=flat-square&logo=android&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-MASVS-000000?style=flat-square&logo=owasp&logoColor=white)
[![JitPack](https://jitpack.io/v/Maignardi/MaigShield.svg)](https://jitpack.io/#Maignardi/MaigShield)

</td>
<td width="50%" valign="top">

### 🔒 [MaigVeil](https://github.com/Maignardi/MaigVeil)

Android **binary hardening suite** that goes beyond R8/ProGuard.

- Gradle plugin with a multi-pass **ASM 9** bytecode transformer
- Per-build polymorphic string encryption and control-flow flattening
- Sensitive calls hidden behind `INVOKEDYNAMIC`
- Custom **C++20 bytecode VM** with per-build shuffled opcodes
- ChaCha20-Poly1305 asset vault and silent anti-repackaging

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![C++20](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle_Plugin-02303A?style=flat-square&logo=gradle&logoColor=white)
![ASM](https://img.shields.io/badge/ASM_9-555555?style=flat-square)
![License](https://img.shields.io/badge/License-Apache_2.0-blue?style=flat-square)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🔐 [MaigSecurityCrypto](https://github.com/Maignardi/MaigSecurityCrypto)

**Kotlin Multiplatform** replacement for the deprecated `EncryptedSharedPreferences` and `EncryptedFile` (Android, iOS and JVM).

- Envelope encryption: **AndroidKeyStore / StrongBox** master key wrapping a **Google Tink** keyset, iOS Keychain on Apple platforms
- Authenticated binary format that blocks file swapping, truncation and algorithm downgrade attacks
- Reactive, type-safe preferences and `@Serializable` object stores built on **Jetpack DataStore**
- Automatic key rotation, biometric binding, secure wipe and migration from legacy `SharedPreferences`
- Nothing leaks to cloud backups by default

![Kotlin Multiplatform](https://img.shields.io/badge/Kotlin_Multiplatform-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-API_23+-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white)
![Tink](https://img.shields.io/badge/Google_Tink-4285F4?style=flat-square&logo=google&logoColor=white)
![DataStore](https://img.shields.io/badge/Jetpack_DataStore-4285F4?style=flat-square&logo=android&logoColor=white)
[![Release](https://img.shields.io/github/v/tag/Maignardi/MaigSecurityCrypto?label=release&style=flat-square&color=2ea44f)](https://github.com/Maignardi/MaigSecurityCrypto/tags)

</td>
</tr>
</table>

---

## 📲 More projects

| Project | What it is | Stack |
|---|---|---|
| [**KMP To-Do List**](https://github.com/Maignardi/KMP_TO_DO_LIST) | Kotlin Multiplatform app sharing UI between Android and iOS | Kotlin · Compose Multiplatform |
| [**Recorder**](https://github.com/Maignardi/Recorder) | Voice recorder with **AI transcription and summaries** (Whisper + Llama via Groq), waveform, trimming and folders | Kotlin · Clean Architecture · Hilt · Room |
| [**NFC Reader**](https://github.com/Maignardi/NFC-READER) | Reads and parses NFC tags on Android | Kotlin · NFC |
| [**Apple Watch Work Timer**](https://github.com/Maignardi/AppleWatchWorkTimer) | Apple Watch app that tells you when your workday ends | Swift · SwiftUI · watchOS |
| [**Watch ↔ Mobile Stopwatch**](https://github.com/Maignardi/stopwatch_watch_connection_to_mobile) | Wear OS stopwatch synced with the phone via the Wearable Data Layer | Kotlin · Compose for Wear OS |
| [**Movies Streaming**](https://github.com/Maignardi/moviesStreaming) | Movie catalog and streaming UI | Kotlin · Jetpack Compose |

---

## 🛠️ Tech stack

**Android**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![KMP](https://img.shields.io/badge/Kotlin_Multiplatform-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

**iOS**

![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=for-the-badge&logo=swift&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=xcode&logoColor=white)

**Cross-platform & web**

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Native, security & backend**

![C++](https://img.shields.io/badge/C++20-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

<div align="center">

💬 **Open to talking about mobile, security and new opportunities.** Reach me on [LinkedIn](https://www.linkedin.com/in/matheus-maignardi/).

</div>
