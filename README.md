<div align="center">

# 📚 PoloCloud Translations

[![License](https://img.shields.io/github/license/HttpMarco/polocloud?style=for-the-badge&color=b2204c)](../LICENSE)
[![Crowdin](https://badges.crowdin.net/polocloud/localized.svg)](https://crowdin.com/project/polocloud)

Centralized translation resources for the PoloCloud ecosystem.

</div>

## 🌍 About

This repository contains structured **translation packs** used by the  
[PoloCloud i18n system](https://github.com/thePolocloud/polocloud-i18n).

Each pack includes:

- 🎯 A `pack.json` metadata manifest  
- 🌐 One or more `.properties` language files  
- 📦 Grouped translations by pack name  
- ⚡ Support for automatic retrieval and caching  

These resources are automatically downloaded and cached by PoloCloud at runtime.


## 📦 What's Inside

Each translation pack should look like:

```
my-pack/
 ├── pack.json
 ├── en_US.properties
 ├── de_DE.properties
 └── ...
```

- `pack.json`: Translation pack info and available languages.
- `*.properties`: Standard key/value translation files.

## 🛠 Usage

This repository is consumed by the PoloCloud-i18n library, which:

1. Downloads pack manifests from GitHub.
2. Caches packs locally.
3. Loads translation files into memory when needed.
4. Provides API access for retrieving localized strings.

No manual management of files is required — packs are fetched and updated automatically.

## 🤝 Contributing

Contributions are welcome!

1. Add new translation packs
2. Improve existing packs

Simply create a PR with your additions or improvements.

> [!IMPORTANT]
> Please update translations only in the default language file (e.g. `en_US.properties`).
> All other languages are managed and synchronized automatically via **Crowdin**  
> and should not be modified manually.

## 🌐 Translate via Crowdin

All community translations are handled through Crowdin.

<div align="center">

### 👉 Help translate PoloCloud  
[Translate on Crowdin](https://crowdin.com/project/polocloud)

</div>

Translations submitted on Crowdin are reviewed and synchronized automatically.

## 📄 License

polocloud-translations is licensed under the [Apache 2.0 License](LICENSE).

<div align="center">

#
    
### 🌐 Translations
Help us translate PoloCloud on [Crowdin](https://crowdin.com/project/polocloud)!

<a href="https://discord.polocloud.de">
    <img alt="PoloCloud Discord" src="https://discord.com/api/guilds/1278460874679386244/widget.png?style=banner2">
</a>

</div>

---

<p align="center">
    This project was created by <a href="https://github.com/RECHERGG/">RECHERGG</a> and the <a href="https://polocloud.de">polocloud.de</a> team.
    <br>
    ©️ 2026 thePolocloud. All rights reserved.
</p>