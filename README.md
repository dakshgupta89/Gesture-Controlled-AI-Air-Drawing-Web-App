# 🎨 AI Gesture Controlled Air Drawing App

Draw in the air using your hand gestures! This project uses **MediaPipe Hands** to detect hand movements through your webcam and lets you draw, erase, or pause without touching the screen.

## 🚀 Features

* ✋ Hand gesture recognition using MediaPipe Hands
* 🎨 Draw with your index finger
* 🧽 Erase using an open palm gesture
* ✊ Pause drawing with a closed fist
* 🌈 Custom brush color picker
* 🖌️ Adjustable brush size
* ✨ Neon glow drawing effect
* 🧹 Clear canvas button
* 📷 Live webcam tracking

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Canvas API
* MediaPipe Hands
* Camera Utils

---

## 📂 Project Structure

```
Air-Drawing-App/
│── index.html
│── README.md
```

---

## 🎮 Controls

| Gesture         | Action |
| --------------- | ------ |
| ☝️ Index Finger | Draw   |
| 🖐️ Open Palm   | Erase  |
| ✊ Closed Fist   | Pause  |

---

## ⚙️ How It Works

1. The browser accesses your webcam.
2. MediaPipe detects your hand landmarks in real time.
3. Hand gestures are analyzed:

   * One index finger extended → Drawing mode
   * Open palm → Eraser mode
   * Closed fist → Pause mode
4. Drawing is rendered on an HTML5 Canvas with a neon glow effect.

---

## ▶️ Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/air-drawing-app.git
```

### Open the project

Simply open `index.html` in your browser.

Or use VS Code with the Live Server extension:

1. Open the project folder.
2. Right-click `index.html`.
3. Select **Open with Live Server**.

> **Note:** Allow camera access when prompted.

---

## 📸 Screenshots

Add screenshots of your application here.

Example:

```
screenshots/
    home.png
    drawing.png
```

---

## 🔮 Future Improvements

* Save drawing as PNG
* Undo and Redo functionality
* Multiple brush styles
* Shape drawing mode
* Multi-hand support
* Dark/Light themes
* Mobile support
* AI gesture customization

---

## 💡 Learning Outcomes

This project helped me learn:

* Real-time hand tracking
* Computer Vision basics
* HTML5 Canvas API
* JavaScript event handling
* Gesture recognition
* MediaPipe integration
* Interactive UI design

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your changes
5. Open a Pull Request

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Daksh Gupta**

Aspiring Full Stack Web Developer passionate about JavaScript, AI-powered web applications, and building interactive user experiences.

If you like this project, don't forget to ⭐ the repository!
