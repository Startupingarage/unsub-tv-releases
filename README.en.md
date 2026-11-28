<div align="center">

<a href="#readme">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/readme/hero-en-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset=".github/readme/hero-en-light.svg">
    <img alt="Unsub TV: one screen instead of seven subscriptions" src=".github/readme/hero-en-dark.svg" width="100%">
  </picture>
</a>

[Русский](README.md) · **English**

<a href="https://github.com/Startupingarage/unsub-tv-releases/releases/latest"><img alt="Latest stable version" src="https://img.shields.io/github/v/release/Startupingarage/unsub-tv-releases?style=for-the-badge&label=version&color=3ddc97&labelColor=0d1311"></a>
<a href="https://github.com/Startupingarage/unsub-tv-releases/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/Startupingarage/unsub-tv-releases/total?style=for-the-badge&label=downloads&color=1fb5c9&labelColor=0d1311"></a>
<img alt="Android TV 8.0+" src="https://img.shields.io/badge/Android%20TV-8.0%2B-7b5cff?style=for-the-badge&labelColor=0d1311">
<img alt="Price: free" src="https://img.shields.io/badge/price-%240%20forever-3ddc97?style=for-the-badge&labelColor=0d1311">

<br><br>

<a href="https://github.com/Startupingarage/unsub-tv-releases/releases/download/v3.1.0/UnsubTV-Companion-0.2.42.apk"><img alt="Download for Android phone" src=".github/readme/btn-android-en.svg" height="56"></a>&nbsp;
<a href="https://github.com/Startupingarage/unsub-tv-releases/releases/download/v3.1.0/UnsubTV-Setup-1.1.49.zip"><img alt="Download for Windows PC" src=".github/readme/btn-windows-en.svg" height="56"></a>&nbsp;
<a href="https://github.com/Startupingarage/unsub-tv-releases/releases/download/v3.1.0/UnsubTV-3.1.0-154.apk"><img alt="Download the TV APK" src=".github/readme/btn-tv-en.svg" height="56"></a>

<sub>The phone or PC and the TV must be on the same home network</sub>

<br>

[**🚀 Quick start (install)**](#quick-start) &nbsp;·&nbsp; [**Why**](#why) &nbsp;·&nbsp; [**Features**](#features) &nbsp;·&nbsp; [**Remote**](#remote) &nbsp;·&nbsp; [**How it works**](#how-it-works) &nbsp;·&nbsp; [**FAQ**](#faq) &nbsp;·&nbsp; [**Privacy**](#privacy)

<br>

<img alt="Unsub TV on a TV: home screen, focused movie, movie actions, My shelf, voice search results, more rows" src=".github/readme/tour-en.svg" width="100%">

</div>

<img src=".github/readme/divider.svg" width="100%" alt="">

## Quick start

> [!IMPORTANT]
> **The latest stable release includes installers, notes, and SHA-256 checksums.** [Open the release](https://github.com/Startupingarage/unsub-tv-releases/releases/latest)

### What to download

| Device | File in Releases | What it is |
| :-- | :-- | :-- |
| 📱 **Android phone** | `UnsubTV-Companion-<version>.apk` | **APK app for your phone.** Installs Unsub TV on the TV, updates it and works as a remote. **Recommended.** |
| 💻 **Windows PC** | `UnsubTV-Setup-<version>.zip` | **Setup wizard for Windows.** Does the same from a PC. |
| 📺 **The TV itself** | `UnsubTV-<version>.apk` | The bare TV app. Only for manual updates. |
| 🔐 | `SHA256SUMS.txt` | Checksums if you want to verify the files. |

> [!TIP]
> Companion and Setup already carry the latest TV APK inside. No need to download it separately.

### Step 1. One network

Connect the phone or PC and the TV to **the same home router**. A guest network or "client isolation" in the router blocks the connection. A VPN on the phone or PC can block the local network too, so turn it off for the setup.

### Step 2. Get the installer

<details open>
<summary><b>📱 From an Android phone</b> &nbsp;<sub>recommended</sub></summary>
<br>

1. Download `UnsubTV-Companion-<version>.apk` from [Releases](https://github.com/Startupingarage/unsub-tv-releases/releases/latest) right on the phone.
2. Open it. If Android asks for permission to install, allow it only for the app you opened the APK with (browser or Files).
3. Launch **Unsub TV Companion** and choose **Set up a new TV**.

</details>

<details>
<summary><b>💻 From a Windows PC</b></summary>
<br>

1. Download `UnsubTV-Setup-<version>.zip` from [Releases](https://github.com/Startupingarage/unsub-tv-releases/releases/latest).
2. Extract the **whole** archive: the wizard won't start from inside the ZIP.
3. Run `UnsubTV-Setup.exe` and choose **New installation**. If Windows warns about an unknown publisher, check the file against `SHA256SUMS.txt` first.

</details>

### Step 3. Connect the TV

The wizard shows where to turn on **Wireless debugging** on the TV. A couple of things people trip over:

- The **connection address** is on the main Wireless debugging screen.
- The **pairing address and six-digit code** are in a separate "Pair device with pairing code" window. Open it when the wizard asks and keep it open until it's confirmed.
- Accept the request on the TV.

### Step 4. Done

Wait for the wizard's final screen: "preparing the file" doesn't mean it's installed yet. Optional steps can be skipped and done later during an update. Then press <kbd>Home</kbd> on the remote and you're in Unsub TV. 🍿

<details>
<summary><b>🔄 How to update</b></summary>
<br>

Grab the latest Companion or Setup from [Releases](https://github.com/Startupingarage/unsub-tv-releases/releases/latest) and choose **Update Unsub TV**. The new version installs over the old one; settings and lists stay.

</details>

<details>
<summary><b>🧯 Can't connect?</b></summary>
<br>

- Make sure both devices are on the same network and it's not guest Wi-Fi.
- Turn off the VPN on the phone or PC and on the TV while connecting.
- After a TV reboot the debugging port may change. Refresh the search in the wizard or enter the current address from the debugging screen.
- If the devices are already paired, you don't need the code again: the connection address is enough.

</details>

**Requirements:** Android TV or Google TV with Android 8.0+ (API 26). The Companion needs Android 8.0+ too.

<img src=".github/readme/divider.svg" width="100%" alt="">

## Why

You pay for five to seven services, then spend the evening jumping between five to seven apps looking for one film. After work you just want to sit down and press play.

**Unsub TV is one home screen for all of it.** YouTube recommendations, films, your apps and your own lists live on one screen you can drive with a plain remote. No Unsub account, no ads, no subscription. It is free and stays free; the project lives on donations only.

<img src=".github/readme/divider.svg" width="100%" alt="">

## Features

<table>
  <tr>
    <td width="33%" valign="top">
      <img src=".github/readme/shots/en/home.jpg" alt="Home screen">
      <h3>🏠 One home screen</h3>
      Recommendations from YouTube and films next to your favorite apps. Focus glows, so you see it from the couch.
    </td>
    <td width="33%" valign="top">
      <img src=".github/readme/shots/en/voice-results.jpg" alt="Voice search results">
      <h3>🎙️ Just say it</h3>
      Press the mic on the remote and say a title, or describe a mood: <i>“classic sci-fi”</i>, <i>“a comedy for tonight”</i>.
    </td>
    <td width="33%" valign="top">
      <img src=".github/readme/shots/en/lists.jpg" alt="My shelf">
      <h3>🔖 My shelf</h3>
      Watch later, continue watching, watched and “don’t suggest”. Everything stays on the TV.
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <img src=".github/readme/shots/en/movie.jpg" alt="Movie card actions">
      <h3>⚡ One click actions</h3>
      Watch, save for later, mark as watched, hide, find similar. Hold <kbd>OK</kbd> on any card.
    </td>
    <td width="33%" valign="top">
      <img src=".github/readme/shots/en/companion.jpg" alt="Android Companion">
      <h3>📱 Phone as a remote</h3>
      The Companion installs and updates the TV app, types searches for you and opens your lists.
    </td>
    <td width="33%" valign="top">
      <img src=".github/readme/shots/en/settings.jpg" alt="Settings">
      <h3>🛠️ Yours to tune</h3>
      Home screen, search, screen and sound, remote and sleep timer. English and Russian out of the box.
    </td>
  </tr>
</table>

<details>
<summary><b>Everything else it does</b></summary>
<br>

- **Search by description.** Add your own Groq key and ask for “space sci-fi from the 70s”. Search by title works without it.
- **Type from your phone.** Scan the QR on the TV and send text from the phone instead of typing with arrows.
- **Updates keep your stuff.** A new version installs over the old one; settings, lists and keys stay.
- **Easy way back.** One switch in settings returns the stock home screen of your TV.
- **Light on old boxes.** Static background, limited downloads and no focus zoom when RAM is low.
- **Works on its own.** After setup the TV needs neither the phone nor an always-on PC.

</details>

<img src=".github/readme/divider.svg" width="100%" alt="">

## Remote

| Press | What happens |
| :-- | :-- |
| <kbd>🎤</kbd> | Voice search from anywhere |
| <kbd>OK</kbd> | Open the card |
| <kbd>OK</kbd> *hold* | More actions: later, watched, hide, similar |
| <kbd>▼</kbd> | Scroll down to continue watching and watch later |
| <kbd>Home</kbd> | Back to Unsub TV |

<img src=".github/readme/divider.svg" width="100%" alt="">

## How it works

```mermaid
flowchart LR
    phone["📱 Companion<br/>Android phone"] -- "install · update · remote" --> tv
    pc["💻 Windows Setup"] -- "install · update" --> tv
    tv(["📺 Unsub TV<br/>your home screen"])
    yt["▶️ YouTube"] -- "your recommendations" --> tv
    films["🎬 Film catalog"] -- "search · posters" --> tv
    rel[("GitHub Releases")] -. "new versions" .-> phone
    rel -. "new versions" .-> pc
```

<img src=".github/readme/divider.svg" width="100%" alt="">

## FAQ

<details>
<summary><b>Is it really free?</b></summary>
<br>
Yes. No subscription, no ads, no paid tier. The project lives on donations only.
</details>

<details>
<summary><b>Will I lose my stock TV home screen?</b></summary>
<br>
No. <b>Settings → Home screen → Home screen → Factory</b> brings it back. To return, open Unsub TV from the app list and switch it back. Apps and accounts stay where they are.
</details>

<details>
<summary><b>Does the TV need my phone or PC to stay on?</b></summary>
<br>
No. They are needed for setup and updates. After that the TV works on its own.
</details>

<details>
<summary><b>Do I need a Groq key?</b></summary>
<br>
No. Search by title and voice work without it. The key only enables search by description, and you can add it later during an update.
</details>

<details>
<summary><b>Which devices are supported?</b></summary>
<br>
Android TV and Google TV boxes and TVs with Android 8.0 or later. The main test device is a Xiaomi TV Box S (3rd gen) with Android 14.
</details>

<img src=".github/readme/divider.svg" width="100%" alt="">

## Roadmap

- [x] English and Russian in the TV app, Android Companion and Windows Setup
- [x] Install and update from a phone or a PC
- [x] Voice search and search by description
- [x] My shelf: watch later, continue, watched, don’t suggest
- [x] New home screen with a big hero card

<img src=".github/readme/divider.svg" width="100%" alt="">

## Privacy

Unsub TV keeps settings, lists, recently opened titles and cached recommendations on the TV. If you add a Groq key, the app encrypts it with Android Keystore and sends the request text to Groq only when you use search by description. Voice input uses the TV’s system speech recognizer.

## Support

Unsub TV is free and always will be. If it saved you a subscription or two, ⭐ star the repo and tell a friend.

## License and credits

Unsub TV is proprietary. All rights reserved. Third-party components keep their own licenses.

Screenshots use demonstration data. Nature and space photographs from Wikimedia Commons: Kevin M. Gill, Jakub Hałun (CC BY 4.0); Michal Klajban, Giles Laurent, Gerda Arendt (CC BY-SA 4.0); Sonse (CC BY 2.0); NASA (public domain). The showcase film posters are in the public domain.

<div align="center">
<br>
<img src=".github/readme/divider.svg" width="60%" alt="">
<br>
<sub>Made for evenings on the couch · <a href="#readme">back to top ↑</a></sub>
</div>
