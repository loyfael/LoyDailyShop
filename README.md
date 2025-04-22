# LoyDailyShop (DailyShop plugin reloaded)

> [!WARNING]  
> ## **Maintenance Only**  
> This is a **community-maintained fork** of the original plugin. I do **not** plan to add new features. This fork only provides **bug fixes** and **updates for new Minecraft versions**. Please do **not request new features**. (They will be instantly rejected).

**An advanced rotating shop plugin for Minecraft (1.16.5 – 1.20.4)**  
DailyShop is a powerful and lightweight shop system that offers configurable rotating item shops. With intuitive GUI customization and Vault integration, it brings a fresh economy experience to your server every day.<br>

Click [**HERE**](https://github.com/loyfael/LoyDailyShop/blob/master/OLD.md) to find the old README.md

---

## ✨ Features

- 🔄 Rotating item shop (daily, weekly, or custom intervals)
- 🛍️ One global shop (free version limitation)
- 🧰 Fully configurable GUI (items, layout, lore, titles, etc.)
- 🌐 Multi-language support via `messages.yml`
- 🔗 Vault integration for economy support
- 🧩 PlaceholderAPI support
- 💾 Persistent storage for player limits and data
- 💡 Lightweight and highly performant

---

## 📦 Installation

1. Download the plugin `.jar` file.
2. Place it in your server’s `plugins/` folder.
3. Restart the server.
4. Configure the plugin using the files generated in `/plugins/DailyShop/`.

---

## 🗂️ Configuration Files

- `config.yml` – Main settings (timers, placeholders, currency, GUI options)
- `messages.yml` – Translatable messages
- `shops/` – Shop definitions (only one supported in free version)
- `storage/` – Player data

---

## 🔧 Commands

| Command | Description |
|---------|-------------|
| `/dailyshop` | Opens the shop GUI |
| `/dailyshop reload` | Reloads all configurations |
| `/dailyshop reset <player>` | Resets a player's data (admin only) |

---

## 🔐 Permissions

| Permission | Description |
|------------|-------------|
| `dailyshop.use` | Allows players to open the shop |
| `dailyshop.reload` | Reload plugin configs (admin) |
| `dailyshop.reset` | Reset player data (admin) |

---

## 📋 Requirements

- Minecraft 1.16.5 – 1.20.4
- Java 17+
- [Vault](https://www.spigotmc.org/resources/vault.34315/)
- (Optional) [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/)

---

## 👤 Author

Developed by **Divios**  
Spigot profile: [https://www.spigotmc.org/members/divios.1078236/](https://www.spigotmc.org/members/divios.1078236/)

---

## 💬 Support

Please use issue section of this github.

---

## 🤝 Contributing

You’re welcome to contribute bug fixes, performance improvements, or version updates.  
Please follow these rules:

- ✅ Only submit **fixes, refactors, version updates and performance improvements**
- ❌ Do **NOT** submit new features or gameplay changes (Yes,i'm sorry)
- ✅ Keep the codebase clean and easy to maintain
- ✅ Respect the original plugin structure and logic
- ✅ Use pull requests for all contributions

Before submitting a PR, please test your changes and include a clear description of what was fixed or improved.

Thanks for helping keep this plugin alive and compatible! ❤️

