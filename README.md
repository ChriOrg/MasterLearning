# 📚 PDF Flashcard Trainer

A minimalist and privacy-first web application that transforms a standard PDF document into an interactive flashcard learning system. Perfectly optimized for digital A6-format flashcards on both mobile devices and desktop browsers.

## ✨ Features
* **Flashcard Mode:** The app automatically picks a random odd page (Question) and keeps the subsequent even page (Answer) hidden until you click to reveal it.
* **Keyboard Navigation:** On PC/Mac, you can study completely hands-free from the mouse – simply press the **Spacebar** or **Enter** key to reveal answers and skip to the next card.
* **100% Privacy-Friendly:** The PDF is processed entirely locally within your browser using `PDF.js`. **Nothing** is uploaded to a server.
* **Mobile-Optimized:** Designed with a mobile-first approach. On iOS (Safari) or Android (Chrome), you can add this page directly to your Home Screen to use it like a native app.

## 🚀 How to Use
1. Open the hosted web app in your browser.
2. Upload your PDF flashcard deck (ideally formatted/exported in A6).
3. Press the **Spacebar** (or tap the button) to reveal the answer.
4. Press the **Spacebar** again to load the next random question.

## 🛠️ Built With
* HTML5 / CSS3
* Vanilla JavaScript
* [PDF.js](https://mozilla.github.io/pdf.js/) by Mozilla (for rendering PDF pages onto HTML5 canvas)
