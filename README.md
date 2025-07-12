# ⏱️ Focus Timer App

Welcome to your new productivity sidekick! 🚀  
This timer app helps you stay laser-focused during work and know exactly when to take short or long breaks—with visual transitions, sound cues, and a playlist to keep you in the zone. 🎧💡

---

## 🎯 What It Does

- 🎵 **Plays relaxing music** while you focus
- 🧘‍♂️ **Lets you switch between focus, short break, and long break modes**
- 📸 **Changes the banner and theme dynamically** for each mode
- 🎬 **Start/pause buttons** with fun sound effects for feedback
- 📲 **Displays countdown in real-time**

---

## 🛠️ Technologies

- **Vanilla JavaScript**
- **HTML5 / CSS3**
- **DOM Manipulation**
- **Audio API**

---

## 📚 How It Works

You choose your mode:
- `Focus`: sets timer to 25 minutes
- `Short Break`: sets timer to 5 minutes
- `Long Break`: sets timer to 15 minutes

Each mode:
- Updates the banner and title text 💬
- Activates background music if toggled 🎶
- Shows a countdown ⏳
- Plays sound effects when the timer starts, pauses, or ends 🔊

```js
musicaFocoInput.addEventListener('change', () => {
  musica.paused ? musica.play() : musica.pause();
});
