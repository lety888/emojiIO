# EmojiIO — Emoji & Special Characters Database

> 🚀 **Live website**: [https://emojiio.com](https://emojiio.com)

**EmojiIO** is a comprehensive open database of emojis, kaomoji (Japanese emoticons), fancy Unicode fonts, and decorative symbols. Perfect for developers, designers, and anyone who loves expressive text.

## ✨ Features

### 🔍 5000+ Emojis with Platform Previews
Browse emojis grouped by category — smileys, animals, food, travel, objects, symbols, and more. Each emoji includes previews from **25 platforms** (Apple, Google, Samsung, Twitter, etc.).

### 🎨 Fancy Unicode Fonts  
Generate stylish text with 25+ Unicode font styles — bold script, gothic, double-struck, monospace, and fraktur. One-click copy & paste.

### ☺️ Kaomoji (Japanese Emoticons)
Hundreds of text-based emoticons organized by emotion and theme: (◕‿◕✿) (╯°□°)╯︵ ┻━┻

### 🎀 Decorative Symbols & Borders
Stars, hearts, arrows, dividers, chess pieces, music notes, and ASCII art frames.

### 🌍 4 Languages
English, 中文, Español, 한국어

## 📁 Data Structure

```
data/
├── emojis/           # Emoji data by category
│   ├── smileys.json
│   ├── animals.json
│   ├── food.json
│   ├── travel.json
│   ├── activities.json
│   ├── objects.json
│   └── symbols.json
├── kaomoji/          # Kaomoji by category
│   ├── happy.json
│   ├── sad.json
│   ├── love.json
│   ├── angry.json
│   ├── anime.json
│   └── ...
├── fonts/            # Fancy font styles
│   └── styles.json
└── decor/            # Decorative symbols
    └── symbols.json
```

## 🛠️ Tech Stack

- **Frontend**: Next.js (App Router)
- **Backend**: Express.js + PostgreSQL
- **Styling**: Tailwind CSS
- **Deployment**: PM2 + Nginx

## 🔗 Links

- **Website**: [https://emojiio.com](https://emojiio.com)
- **Product Hunt**: [Coming soon]

## 📄 License

MIT
