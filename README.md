# 🎧 Audio Cleaner for Adobe After Effects  
*An open-source silence remover script panel for editors, built with ❤️ by EAT (Talha)*

---

## 🧠 What Is This?

**Audio Cleaner** is a dockable panel for Adobe After Effects that automatically detects silent parts in your audio and trims or isolates them from your video/still layers. It’s perfect for interviews, voiceovers, tutorials — or anywhere you're tired of editing out long awkward silences manually 😅

I built this by learning from existing ideas and tools, then creating my own version with a simpler, customizable interface and clean integration into AE. All code is written and structured independently.

---

## ✨ Features

- 🔇 **Silence Detection**: Automatically finds low-volume audio zones
- 🎚️ **Adjustable Threshold**: Customize the dB level that counts as “silence”
- 🧈 **Audio Padding**: Add frame buffers to avoid abrupt cuts
- 🔄 **Multiple Modes**:
  - Remove silence with ripple delete
  - Isolate silence instead of sound
  - Keep gaps (preserve timing, no ripple)
- 🖼️ **Clean Dockable UI**: Works like any AE panel

---

## 🔧 How to Use

1. **Download the script** (`AudioCleaner_V1_by_EAT.jsx`)
2. Open **After Effects**
3. Go to:  
   `File > Scripts > Run Script File...`
4. Select the `.jsx` file
5. The **Audio Cleaner panel** will open — dock it anywhere
6. Select the **video/still layer** you want to trim
7. Make sure an **audio layer** exists in your composition
8. Set your preferences:
   - Silence threshold
   - Frame padding
   - Modes (invert, ripple-delete, etc.)
9. Click **"Start Cleaning"** and let it do its thing 🎬

---

## 📢 Notes

This is a repurposed tool built from ideas and practices I studied online, but the code, UI, and logic are my own implementation.  
No direct code was copied. This version is built for public and educational use only.

---

## 🗣️ Feedback? Suggestions?

This is just the first version. I’m planning:
- 📝 Documentation & quick-start guide
- 👁️ Preview-before-cutting feature
- 🖌️ UI & experience improvements

Feel free to:
- ⭐ Star it
- 🛠️ Fork it
- 🐞 Report bugs
- 💡 Suggest features

Drop an issue or comment — or hit me up on Reddit/Quora when I post it!

---

## 🔗 [Link to this repository]
