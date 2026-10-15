# XGoogle

Google features for the **Xiaomi HyperOS 4 China ROM** — a fork of [Coogle](https://github.com/zopulus/coogle) by [@zopulus](https://github.com/zopulus), ported from ColorOS to HyperOS.

## Features
- Long-press power → Gemini / Google Assistant
- Long-press the navigation handle → Circle to Search (needs the companion module; with 3-button navigation, long-press Home)
- "Hey Google" voice activation (needs the companion module)
- Circle to Search live translate (keeps translating as you scroll; needs the companion module)
- Google Lens
- Android Auto (system app and car projection role, via the companion module)
- Removes the GMS China restriction (Quick Share included, with its control center tile)
- Experimental: lock screen shortcuts, control center Lens tile, double-press power → Google Wallet, Lens button in the camera
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
System Framework, System UI, Settings, Google, XiaoAi (`com.miui.voiceassist`), Always-on display (`com.miui.aod`), Security (`com.miui.securitycore`), Google Wallet. Camera is optional (Lens button).
Do not uninstall XiaoAi: the navigation handle reaches Circle to Search through it.

## Companion module
Hey Google, Circle to Search from the navigation handle, live translate and Android Auto need the companion module. XGoogle offers to install it (and to update it when it is out of date), or download it from [GitHub releases](https://github.com/Leekin2/XGoogle/releases).

## Source code and support
- Source: https://github.com/Leekin2/XGoogle (GPL-3.0)
- Feedback and complaints on Telegram: [@emcleek](https://t.me/emcleek)
- Support group: [Xgoogle for HyperOS](https://t.me/Xgooogle)

Credits: [@zopulus](https://github.com/zopulus), [@MiToverG422](https://github.com/MiToverG422), [@luckyzyx](https://github.com/luckyzyx), [@tiann](https://github.com/tiann), [@LuckyPray](https://github.com/LuckyPray), [Miuix](https://github.com/compose-miuix-ui/miuix).
Not affiliated with Google or Xiaomi.
