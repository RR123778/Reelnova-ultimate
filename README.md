# 🎬 AI Video Generator (Canvas Based)

A simple browser-based AI video generator that converts a text prompt into animated scenes, voice narration, and downloadable video — all using pure HTML + JavaScript (No backend required).

---

## 🚀 Features

- ✍️ Generate script from user input
- 🎥 Scene-by-scene canvas animation
- 🔊 Text-to-speech (voice narration)
- ⏺️ Record canvas as video (WebM)
- 📥 Download generated video
- 📱 Share via WhatsApp
- ⚡ Fully frontend project (no server needed)

---

## 🛠️ How It Works

1. Enter a topic/prompt  
2. Script is auto-generated into multiple scenes  
3. Scenes play on canvas (2 seconds each)  
4. Voice narration reads the script  
5. Canvas gets recorded as a video  
6. Download or share the video  

---

## 📂 Project Structure

```
project-folder/
│
├── index.html
├── script.js
└── style.css (optional)
```

---

## 🧠 Functions Overview

### generate()
Creates scenes from user input.

### playVideo()
Starts scene animation.

### drawScene(text)
Displays text on canvas.

### wrapText()
Handles multi-line text formatting.

### speakAll()
Reads full script using speech synthesis.

### record()
Records canvas using MediaRecorder.

### download()
Downloads the recorded video.

---

## ⚠️ Notes

- Best supported in Chrome / Edge browser  
- Some mobile browsers may not support recording  
- Output video format: `.webm`  
- Speech voice depends on device  

---

## 🧪 Example Prompt

```
How to earn money online
```

---

## 💡 Future Improvements

- Add real AI API (OpenAI / Gemini)
- Add background images & transitions
- Export video in MP4
- Add subtitles
- Multi-language support

---

## 📲 WhatsApp Share Link

```
https://wa.me/?text=Check this AI tool
```

---

## 👨‍💻 Author

Ramjee Life Care  
Email: ramramjee491@gmail.com  

---

## ⭐ Support

If you like this project:
- Star the repo ⭐
- Share it
- Customize and improve it
