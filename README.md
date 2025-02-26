# Modern Alarm App

![Alarm App Screenshot](https://via.placeholder.com/800x400?text=Alarm+App+Screenshot)

## Overview

A sleek, modern web-based alarm application built with vanilla JavaScript, HTML, and CSS. This app allows users to set multiple alarms with a clean, intuitive interface featuring a glassmorphic design.

## Features

- **Real-time Clock Display**: Shows the current time in 24-hour format
- **Multiple Alarms**: Add as many alarms as needed
- **Toggle Functionality**: Enable or disable alarms without deleting them
- **Delete Individual Alarms**: Remove specific alarms as needed
- **Clear All**: One-click option to remove all alarms
- **Modern UI**: Glassmorphic design with subtle blur effects and gradient accents
- **Responsive Design**: Works on desktop and mobile devices
- **Audio Alerts**: Plays sound when alarm time is reached

## Technologies Used

- HTML5
- CSS3 (with modern effects like backdrop-filter)
- Vanilla JavaScript
- LocalStorage API (coming soon)

## How to Use

1. **View the current time** displayed at the top of the app
2. **Set a new alarm**:
   - Enter the hour (0-23)
   - Enter the minute (0-59)
   - Click "Add Alarm"
3. **Manage alarms**:
   - Toggle the switch to activate/deactivate an alarm
   - Click the trash icon to delete an individual alarm
   - Use "Clear All" to remove all alarms at once

## Installation

No installation required! Simply open the `index.html` file in any modern web browser.

```bash
# If you have Python installed, you can run a simple HTTP server:
python -m http.server

# Then open http://localhost:8000 in your browser
```

## Project Structure

- `index.html` - Main HTML structure
- `styles.css` - Styling and responsive design
- `script.js` - Application logic and functionality
- `alarm.mp3` - Audio file for alarm sound

## Planned Features

- **Persistent Storage**: Save alarms between sessions using LocalStorage
- **Custom Alarm Sounds**: Allow users to choose from multiple alarm tones
- **Snooze Functionality**: Add ability to snooze alarms for a set time
- **Labeled Alarms**: Add custom text labels to alarms
- **Recurring Alarms**: Set alarms for specific days of the week
- **Dark/Light Theme Toggle**: Allow users to switch between visual themes
- **Countdown Timer**: Add a countdown display for upcoming alarms
- **Alarm Categories**: Organize alarms by purpose (work, medication, etc.)
- **Export/Import**: Share alarm configurations between devices
- **Push Notifications**: Browser notifications for alarms (when tab is not active)
- **Accessibility Improvements**: Enhanced keyboard navigation and screen reader support

## Browser Compatibility

Tested and working on:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+


## Acknowledgments

- Inspired by modern UI/UX design principles
- Sound effects from [OpenGameArt.org](https://opengameart.org/)