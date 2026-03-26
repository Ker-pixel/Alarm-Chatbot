# WAKE UP CHALLENGE

**The no-excuses system to wake up early and train your brain first thing in the morning!**

This project is a mobile-friendly web app combined with iPhone Shortcuts automation to help you wake up at 6:00 AM, complete a mini brain challenge, and track your streaks.

---

## Features

- 🧠 3 Brain Challenges (Awake confirmation, typing, math)
- 🔥 Streak tracking (current streak, best streak, total days)
- ⚡ Auto-start between 5:45-7:00 AM
- 📱 Mobile optimized with vibration feedback
- 🏆 Milestones for consistent wake-ups
- 🖤 Daring, no-nonsense text to keep you motivated

---

## Setup Instructions

### 1. iPhone Shortcut Setup

#### Create a Daily Wake-Up Automation

1. Open the **Shortcuts** app.
2. Go to `Automation → + → Create Personal Automation → Time of Day → 6:00 AM → Daily`.
3. Turn **Ask Before Running** OFF.

#### Add Actions

1. **Show Notification**
   - Title: `WAKE UP ⚠️`
   - Body: `Your challenge is waiting. NO EXCUSES.`
   - Sound: Loud tone (optional)
2. **Open URL**
   - Paste this [GitHub Pages](https://ker-pixel.github.io/Alarm-Chatbot/) link.
3. Optional: **Play Sound / Vibrate** for stronger wake-up effect.

#### Optional Hardcore Actions

- Ask for text input (`"Type 'I am awake'"`) before opening the page.
- Conditional challenge based on your streak.
- iCloud file read/write to sync streaks across devices.

### 2. Add to Home Screen

1. Open the page in Safari.
2. Tap **Share → Add to Home Screen**.

---

## How It Works

1. At 6:00 AM, the Shortcut sends a notification and opens the web app.
2. The app auto-starts if opened between 5:45-7:00 AM.
3. Complete 3 challenges:
   - Q1: Confirm you're awake
   - Q2: Type a sentence exactly
   - Q3: Solve a math problem
4. Streaks and milestones are tracked using browser `localStorage`.
5. If you skip a day, your streak resets.

---
## Notes

- Works best on iPhone Safari.
- Page must be added to Home Screen for fullscreen experience.
- Vibration requires a supported device.

---

**This system isn’t for the faint-hearted. Prepare to wake up and dominate your mornings!**

