# 🧪 Sieve Text

A lightweight web app that checks whether a message looks like spam, right in your browser. No backend, no sign-up, no data leaves your device.

**Live demo:** https://vsmadhav-dev.github.io/SieveText/

---

## Features

- Paste any message and get an instant **Spam / Not Spam** verdict
- A **spam score** with the reasons behind it, so you can see *why* a message was flagged
- 100% client-side: your text is never uploaded anywhere
- Clean, responsive interface that works on phone and desktop
- Built with plain HTML, CSS and vanilla JavaScript, with zero dependencies

## Tech stack

- **HTML5** for structure
- **CSS3** for styling and responsive layout
- **JavaScript (ES6+)** for the regex detection logic and DOM updates

## Getting started

```bash
# 1. Clone the repository
git clone https://github.com/vsmadhav-dev/SieveText.git

# 2. Open the folder
cd SieveText

# 3. Open index.html in your browser
```

No build step or installation needed. You can also use the VS Code **Live Server** extension for auto-reload while editing.

## Project structure

```
SieveText/
├── index.html    # App layout
├── style.css     # Styling
├── script.js     # Spam detection logic
└── README.md
```

## Limitations

- Detection depends on a fixed set of regex patterns, so new spam styles may slip through
- Currently tuned for English-language messages
- No learning from user feedback

## Roadmap

- [ ] Support for Hindi and Hinglish spam patterns
- [ ] Adjustable sensitivity slider
- [ ] Highlight the exact text each regex matched
- [ ] Try a Naive Bayes classifier in JavaScript for smarter detection
- [ ] Sample messages to test with one click

## Contributing

Suggestions and pull requests are welcome. If you find a message that fools the detector, open an issue with the example.