# 🎧 Audio Cleaner for Adobe After Effects  
*An open-source silence remover script panel for editors, built with ❤️ by EAT (Talha)*

---

## 🧠 What Is This?

**Audio Cleaner** is a dockable panel for Adobe After Effects that automatically detects silent parts in your audio and trims or isolates them from your video layer. Ideal for interviews, voiceovers, tutorials, or podcast edits — basically, anywhere you're tired of cutting silence manually.

This was inspired by tools like **Void Silence Remover** from [SolidState School](https://solidstate.school/void-silence-remover/). I built my own from scratch with a simple UI and customizable options.

---

## ✨ Features

- 🔇 **Silence Detection**: Automatically detects quiet parts of audio
- 🎚️ **Adjustable Threshold**: Customize how quiet is considered “silent”
- 🧈 **Audio Padding**: Add buffer frames to avoid cutting off speech
- 🛠️ **Multiple Modes**:
  - Remove silence and ripple-delete timeline
  - Isolate only the silent sections
  - Keep gaps while trimming, to preserve timing
- 🖼️ **Clean Dockable UI**: Seamlessly fits into your AE workspace

---

## 🔧 How to Use

1. **Download the script file** (`AudioCleaner_V1_by_EAT.jsx`)
2. In **After Effects**, go to:  
   `File > Scripts > Run Script File...`
3. Select the `.jsx` file
4. A panel will appear – dock it if you want
5. Select the **video/still layer** you want to trim  
6. Make sure an **audio layer** exists in your comp
7. Adjust the settings:
   - Silence threshold
   - Frame padding
   - Mode (invert, ripple-delete, etc.)
8. Click **"Start Cleaning"** 🧽

---

## 📢 Disclaimer & Credit

This tool was built by me (Talha) by referencing the idea behind **Void Silence Remover**, but all the code is original and customized for personal and community use. No code was copied from their repository.

If you're from SolidState and you'd like me to credit differently or modify the script in any way, just reach out! 🙏

---

## 🗣️ Feedback? Suggestions?

This is still V1 — more features like:
- 📝 Documentation
- 💡 Preview before cutting
- 🎛️ Improved UI
are coming soon.

Feel free to fork, use, and suggest what you want added!

👉 Drop issues or pull requests  
👉 Message me on Reddit/Quora when I post it 😄

---

## 🔗 [Link to this repository]
