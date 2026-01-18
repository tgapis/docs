
# 📚 Telegram Docs Bots

Welcome 👋🏻  
This project provides **instant access to Telegram Bot API and Telethon (TL) API methods** using powerful inline Telegram bots. No more browsing docs again and again.. just search and get results instantly 🚀

---

## 🤖 @TdocsBot — Telegram Bot API Docs

Use **inline search** to quickly find any Telegram **Bot API** method.

### How to use

@TdocsBot <query>

Search anywhere in Telegram using inline mode.

### Example searches
- `sendMessage`
- `getUpdates`
- `editMessageText`

🔍 Fast • Simple • Inline

⚠️ This bot is **not affiliated with Telegram**  
Made by [Ankit](https://t.me/ankify) for personal use.

---

## 🤖 @TldocsBot — Telethon (TL) API Docs

Instant search for **Telethon raw API (TL-schema) methods** with flexible output formats.

### Inline usage

@TldocsBot <query>

### 🔑 Prefix Usage Guide

| Prefix | Result |
|------|------|
| `.query` | Import link only |
| `/query` | Import + parameters |
| `!query` | Import + example + link |
| `` `query `` | Example + link |
| `query` | Full method details |

### Example searches
- `SendMessageRequest`
- `DeleteChatRequest`
- `EditMessageRequest`

🎉 Created by **[Ankit Chaubey](https://t.me/AnkitChaubey)**  
Telegram: [@ankify](https://t.me/ankify)  
GitHub: https://github.com/ankit-chaubey 🧑🏻‍💻

---

## 🔄 Automatic Updates

This project is **fully automated**:

- Scrapes official Telegram & Telethon documentation
- Regenerates JSON schemas automatically
- Publishes updated docs regularly using CI workflows

No manual updates needed ✨

---

## 🌐 Published Resources

- **Bot API JSON**  
  👉 https://tgapis.github.io/x/botapi.min.json

- **Telethon TL Documentation**  
  👉 https://tgapis.github.io/x/Telegram/

- **Interactive TL-Schema Explorer**  
  👉 https://tgapis.github.io/schema.tl/

- **Telethon diff.telethon.dev Fork**
  - Desktop: https://tgapis.github.io/x/TL/diff/tdesktop.html  
  - TDLib: https://tgapis.github.io/x/TL/diff/tdlib.html

---

## ❤️ Notes

- Built for speed, clarity, and developer convenience
- Ideal for **bot developers**, **Telethon users**, and **Telegram power users**
- Open-source & continuously improving

Enjoy exploring Telegram APIs effortlessly 🚀

## 🙏 Thanks & Credits

Special thanks to **PaulSonOfLars** (@PaulSonOfLars) for the Telegram Bot API specification  
 - https://github.com/PaulSonOfLars/telegram-bot-api-spec

Big thanks to **SpEcHiDe** (@SpEcHiDe) for maintaining Telegram API resources  
 - https://github.com/TelegramPlayground/TG-APIs

Grateful to **Lonami** (@LonamiWebs) for Telethon and TL diff tools  
 - https://github.com/LonamiWebs/Telethon  
 - https://github.com/Lonami/tl-differ
