# 25 + 5 Clock (Pomodoro Timer)

⏱️ A productivity timer based on the Pomodoro Technique, alternating between 25-minute work sessions and 5-minute breaks.

## Features 🌟
- 🕒 **Adjustable Timers**: Customize work (25min default) and break (5min default) durations
- ⏯️ **Play/Pause**: Start and stop the timer
- 🔁 **Reset**: Quickly reset all settings to default
- 📱 **Responsive**: Works on mobile and desktop devices

## Live Demo
👉 [https://twentyfive-plus-five-clock.onrender.com/](https://twentyfive-plus-five-clock.onrender.com/)

## Installation
```bash
# Clone the repository
git clone https://github.com/maker-dev/twentyfive-plus-five-clock.git
cd twentyfive-plus-five-clock

# Install dependencies
npm install

# Start development server
npm run dev
```

## Technologies Used
- ⚛️ React with Hooks (useState, useEffect, useRef)
- 🎨 CSS Modules/Styled Components
- ⏲️ JavaScript timing functions

## Default Settings
- Session Length: 25 minutes
- Break Length: 5 minutes

## How to Use
1. Set your desired work and break lengths using the +/- controls
2. Click the play button to start the timer
3. Work until the timer completes (you'll hear a chime)
4. Take a break when the timer switches
5. After 4 cycles, enjoy a longer break
