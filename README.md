# XGoogle

Google features for the **Xiaomi HyperOS 4 China ROM**.

## Features
- Long-press power → Gemini / Google Assistant
- Long-press the navigation handle → Circle to Search (needs the companion module; with 3-button navigation, long-press Home)
- Swipe in from the side and hold → Circle to Search (needs XiaoAi, see Scopes)
- Gestures are optional: for the handle hold, the side swipe-and-hold and the double tap, choose Circle to Search or XiaoAi
- "Hey Google" voice activation (needs the companion module)
- Circle to Search live translate (keeps translating as you scroll; needs the companion module)
- Google Lens
- Android Auto (system app and car projection role, via the companion module)
- Removes the GMS China restriction (Quick Share included, with its control center tile; "View downloads" opens File Manager)
- Optional: Google Maps Timeline, passkeys and password manager
- Experimental: lock screen shortcuts, control center Lens and Circle to Search tiles, double-press power → Google Wallet, Lens button in the camera
- Two looks: Material, or HyperOS style (light/dark/system theme, wallpaper colors, frosted bar)
- Status card that lists the apps still unticked in LSPosed and tells you when the companion module needs an update; restart apps without rebooting; update check
- UI languages: Türkçe, English, Русский, Español, 简体中文

Every feature can be toggled on its own.

## Specs
- Size: app ~4 MB, companion module ~0.45 MB
- RAM: no extra cost (the Google assistant process uses ~90 MB, as on any Android phone)
- Companion module auto-updates in your root manager; uninstalling it restores your key settings
- HyperOS one-key clean no longer kills the Google assistant

## Requirements
- Xiaomi HyperOS 4 China ROM (Android 17), tested on Xiaomi 15 Ultra
- KernelSU / SukiSU, LSPosed (API 102), Google app

## Scopes
System Framework, System UI, Settings, Google, Always-on display (`com.miui.aod`), Security (`com.miui.securitycore`), Google Wallet. Camera is optional (Lens button).
XiaoAi (`com.miui.voiceassist`) is no longer needed: XGoogle opens Circle to Search from the navigation handle in the system itself, so you can uninstall XiaoAi. If you keep it, leave it ticked: it stays as a fallback. The side swipe-and-hold is offered by HyperOS only while XiaoAi is installed: keep XiaoAi ticked and set that gesture to XiaoAi's ball, and XGoogle opens Circle to Search instead.
Optional features ask for their own scopes when switched on: Google Play services, Google Services Framework and Maps for Timeline; Security (`com.miui.securitycenter`) and Scanner for passkeys.
Use Hybrid Mount as the metamodule; Mountify can hide the ROM's own system files.

## Companion module
Hey Google, Circle to Search from the navigation handle, live translate and Android Auto need the companion module. XGoogle offers to install it (and to update it when it is out of date), or download it from [GitHub releases](https://github.com/Leekin2/XGoogle/releases).

## Source code and support
- Source: https://github.com/Leekin2/XGoogle (GPL-3.0)
- Feedback and complaints on Telegram: [@emcleek](https://t.me/emcleek)
- Support group: [Xgoogle for HyperOS](https://t.me/Xgooogle)

Credits: [@zopulus](https://github.com/zopulus), [@MiToverG422](https://github.com/MiToverG422), [@luckyzyx](https://github.com/luckyzyx), [@tiann](https://github.com/tiann), [@LuckyPray](https://github.com/LuckyPray), [Miuix](https://github.com/compose-miuix-ui/miuix).
Not affiliated with Google or Xiaomi.
