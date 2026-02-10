# 📖 Dictionary Web App

An interactive dictionary web application that fetches word definitions, examples, synonyms, and pronunciations using the **Free Dictionary API**.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![API](https://img.shields.io/badge/REST_API-009688?style=for-the-badge&logo=fastapi&logoColor=white)

## 🔗 Live Demo

**[Try it now →](https://raulabakarov.github.io/DictionaryWebApp/)**

## ✨ Features

- 🔍 **Word Search** — Type any English word and press Enter
- 📚 **Definitions** — Get detailed word meanings
- 💬 **Examples** — See words used in context
- 🔗 **Synonyms** — Discover related words (clickable!)
- 🔊 **Pronunciation** — Listen to audio pronunciation
- 🎨 **Clean UI** — Modern, minimalist design

## 🚀 Getting Started

### Online
Visit the [live demo](https://raulabakarov.github.io/DictionaryWebApp/)

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/RaulAbakarov/DictionaryWebApp.git
   cd DictionaryWebApp
   ```

2. Open `index.html` in your browser

## 🏗️ Project Structure

```
DictionaryWebApp/
├── index.html     # Main HTML structure
├── script.js      # API calls and DOM manipulation
├── style.css      # Styling
└── source/        # Additional assets
```

## 🛠️ Technical Details

### API Integration
Uses the [Free Dictionary API](https://dictionaryapi.dev/):
```javascript
fetch(`https://api.dictionaryapi.dev/api/v2/entries/en/${word}`)
```

### Features Implementation
- **Async/Await** for API calls
- **Dynamic DOM** updates
- **Audio playback** for pronunciations
- **Error handling** for unknown words

## 📸 Preview

| Feature | Description |
|---------|-------------|
| Search | Enter any word and press Enter |
| Results | View definition, phonetics, examples |
| Audio | Click speaker icon to hear pronunciation |
| Synonyms | Click any synonym to search it |

## 🎯 How to Use

1. Type a word in the search box
2. Press `Enter` to search
3. View the definition, part of speech, and phonetics
4. Click 🔊 to hear pronunciation
5. Click on synonyms to explore related words

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Raul Abakarov** — [GitHub](https://github.com/RaulAbakarov) | [LinkedIn](https://linkedin.com/in/raulabakarov)

---

⭐ Found this useful? Give it a star!
