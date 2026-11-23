<div align="center">

<p align="center">
  <img src="https://github.com/VengeanceUtilities.png" alt="Vengeance Player Logo" width="120" style="border-radius: 50%;">
</p>

# ⚡ Vengeance Player

**Hybrid Music Streaming & Custom DSP Audio Engine for Android**

[![Version](https://img.shields.io/badge/VERSION-5.3-purple?style=for-the-badge)](https://github.com/VengeanceUtilities/VengeancePlayer/releases/latest)
[![Platform](https://img.shields.io/badge/PLATFORM-ANDROID-brightgreen?style=for-the-badge&logo=android)](https://github.com/VengeanceUtilities/VengeancePlayer/releases)
[![Website](https://img.shields.io/badge/WEBSITE-vengeanceutilities.de-blue?style=for-the-badge)](https://vengeanceutilities.de)
[![Instagram](https://img.shields.io/badge/INSTAGRAM-@GODLYECHELON-E4405F?style=for-the-badge&logo=instagram)](https://instagram.com/godlyechelon)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-yellow.svg?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)

<br/>

<a href="https://github.com/VengeanceUtilities/VengeancePlayer/releases/latest">
  <img src="https://img.shields.io/badge/Download-Latest%20APK-blue?style=for-the-badge&logo=android&logoColor=white" height="42" alt="Download APK" />
</a>

</div>

---

## Overview

**Vengeance Player** brings **YouTube Music** and **Spotify** together in a single, ad-free Android client. Built from the ground up with Jetpack Compose and Media3, version **5.3** introduces a custom 10-band DSP audio pipeline, frequency-aware DJ crossfading, live audio/video switching, and a 120Hz refractive glass UI driven by AGSL shaders.

---

## Screenshots

<table>
  <tr>
    <td align="center" width="33.33%">
      <img src="https://github.com/user-attachments/assets/056d0d1b-0f26-4d5a-84de-761b769d523c" width="100%" alt="Vengeance Player - Home Page" />
    </td>
    <td align="center" width="33.33%">
      <img src="https://github.com/user-attachments/assets/3eafba36-8dfb-46e6-829e-0fcfb63dfe19" width="100%" alt="Vengeance Player - Player Page" />
    </td>
    <td align="center" width="33.33%">
      <img src="https://github.com/user-attachments/assets/3798841a-5649-418a-8cf0-85eeac95e156" width="100%" alt="Vengeance Player - Library Page" />
    </td>
  </tr>
  <tr>
    <td align="center" width="33.33%">
      <img src="https://github.com/user-attachments/assets/2f34eca1-101f-4be2-9807-ce0ebdd6aa7b" width="100%" alt="Vengeance Player - Spotify Songs Page" />
    </td>
    <td align="center" width="33.33%">
      <img src="https://github.com/user-attachments/assets/4a2617d2-6023-4cfc-95bf-d8080312835c" width="100%" alt="Vengeance Player - Appearance Page" />
    </td>
    <td align="center" width="33.33%">
      <img src="https://github.com/user-attachments/assets/016b2c92-26c2-4945-b07a-1d071990c05e" width="100%" alt="Vengeance Player - Recap Page" />
    </td>
  </tr>
</table>

---

## What's Inside v5.3

### Hybrid Playback & Smart Switching
- **Unified Catalog:** Browse, search, and queue tracks across YouTube Music and Spotify inside one library.
- **Auto-Fallback Resolver:** If a stream fails or hits a regional block on one platform, Vengeance automatically resolves and plays the matching track from the other source without interrupting playback.
- **Instant Audio / Video Toggle:** Switch between cover art and the music video mid-track without losing your current timestamp.
- **Ad-Free & Offline Ready:** Uninterrupted background playback, unlimited skips, and local caching/downloads for tracks, albums, and playlists.

### Custom DSP & Audio Pipeline
- **10-Band Equalizer & Limiter:** Powered by Android's `DynamicsProcessing` API (with automatic fallback for older devices) and a built-in `-2 dB` limiter to prevent clipping.
- **Sub-Bass Punch & Vocal Reducer:** Dedicated low-end boost for bass-heavy tracks alongside a mid-range notch filter ("Sing Mode") that ducks vocals on the fly.
- **EQ-Automix Crossfade:** Configurable track transitions (up to 12s) that dynamically attenuate low-end frequencies during the overlap so basslines don't clash.
- **Smart Sleep Timer:** Smooth volume fade-out or automatic stop at the end of the current track.

### Refractive Glass UI & Motion
- **120Hz Reactive Cover Stage:** Gyroscope-driven 3D tilt, real-time bass aura via AGSL `RuntimeShader`, specular glass borders, and gesture controls (swipe to skip, double-tap edges to seek ±10s).
- **Dual-Anchor Color Engine:** Extracts deep AMOLED-safe ambient tones and high-contrast vibrant accents from every album cover.
- **Kinetic Lyrics & Story Cards:** Word-by-word synced lyrics with tap-to-seek, plus a built-in 9:16 glassmorphism share-card generator for Instagram Stories.
- **Android Auto & In-App Updater:** Full head-unit integration for driving and direct APK update checks via GitHub Releases.

---

## Installation

1. Open the [Latest Release](https://github.com/VengeanceUtilities/VengeancePlayer/releases/latest) page.
2. Download `Vengeance.Player.5.3.apk`.
3. Allow installation from unknown sources if prompted by Android.
4. Install and launch the app.

---

## Tech Stack

- **Language:** Kotlin & Coroutines / Flow
- **UI & Graphics:** Jetpack Compose, Material 3 Expressive, AGSL `RuntimeShader`, Haze Blur, Coil 3
- **Audio & Playback:** AndroidX Media3 / ExoPlayer, `DynamicsProcessing` DSP Engine, `Visualizer` FFT/Bass Tracking
- **Car Integration:** Android Auto (`MediaBrowserService` & `MediaSession`)
- **Networking & Storage:** Ktor, OkHttp, Room Database

---

## Credits

Vengeance Player builds upon open-source foundations from:
- **InnerTune** by [z-huang](https://github.com/z-huang/InnerTune)
- **ArchiveTune** by [rukamori](https://github.com/rukamori/ArchiveTune)

---

## License

Distributed under the **GNU General Public License v3.0 (GPL-3.0)**. See the `LICENSE` file in this repository for details.

> Actively maintained and updated regularly. Found a bug or have a feature idea? Reach out on Discord or Instagram:
>
> [![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/GCU3SU5fKH)
