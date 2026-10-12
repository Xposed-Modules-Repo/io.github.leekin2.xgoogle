# XGoogle

Google features for the **Xiaomi HyperOS 4 China ROM** — a fork of [Coogle](https://github.com/zopulus/coogle) by [@zopulus](https://github.com/zopulus), ported from ColorOS to HyperOS.

## Features
- Long-press power → Gemini / Google Assistant
- Long-press the navigation handle → Circle to Search
- "Hey Google" voice activation (needs the companion module)
- Circle to Search live translate (keeps translating as you scroll)
- Google Lens
- Android Auto (system app and car projection role, via the companion module)
- Removes the GMS China restriction (Quick Share included)
- Experimental: lock screen shortcuts, control center Lens tile, double-press power → Google Wallet
- UI languages: Türkçe, English, Русский, Español, 简体中文

Every feature can be toggled on its own.

## Specs
- Size: app ~3.2 MB, companion module ~0.45 MB
- RAM: no extra cost (the Google assistant process uses ~90 MB, as on any Android phone)
- Battery: ~0 with Hey Google off; roughly 5–10% per full charge with it on (software detection)
- Companion module auto-updates in your root manager; uninstalling it restores your key settings
- HyperOS one-key clean no longer kills the Google assistant

## Requirements
- Xiaomi HyperOS 4 China ROM (Android 17), tested on Xiaomi 15 Ultra
- KernelSU / SukiSU, LSPosed (API 102), Google app

## Scopes
System Framework, System UI, Settings, Google, XiaoAi (`com.miui.voiceassist`), Always-on display (`com.miui.aod`).
Do not uninstall XiaoAi: the navigation handle reaches Circle to Search through it.

## Companion module
Hey Google and Android Auto need the companion module. Turn on Hey Google in XGoogle to install it, or download it from [GitHub releases](https://github.com/Leekin2/XGoogle/releases).

## Source code and support
- Source: https://github.com/Leekin2/XGoogle (GPL-3.0)
- Telegram channel: https://t.me/xioamifetiscisi
- Feedback and suggestions: [@emcleek](https://t.me/emcleek)

Credits: [@zopulus](https://github.com/zopulus), [@MiToverG422](https://github.com/MiToverG422), [@luckyzyx](https://github.com/luckyzyx), [@tiann](https://github.com/tiann), [@LuckyPray](https://github.com/LuckyPray).
Not affiliated with Google or Xiaomi.