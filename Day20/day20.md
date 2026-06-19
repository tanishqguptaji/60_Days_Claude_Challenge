# Day 20 – AI Face Puzzle Game

## Objective

Today's challenge focused on building a complete AI-powered Face Puzzle Game using Claude.

The application captures a user's face through the webcam, automatically converts the image into puzzle pieces, and creates an interactive drag-and-drop puzzle experience with timers, scoring, and leaderboards.

---

# Challenge Overview

Claude was used as:

- Front-End Developer
- UI/UX Designer
- Game Developer
- JavaScript Engineer

The goal was to create a fully functional browser-based puzzle game using a single HTML file.

---

# Features Implemented

## 📸 Camera Integration

The application successfully:

- Requested webcam permission using `getUserMedia()`
- Displayed a live camera preview
- Allowed face capture through a "Take Photo" button
- Generated puzzle images directly from captured photos

---

## 🧩 Puzzle Generation

After capturing the photo:

- Difficulty selection available
  - 3×3 Grid
  - 4×4 Grid
  - 5×5 Grid

- Image automatically sliced into puzzle pieces
- Puzzle pieces scrambled into randomized positions
- Solvable puzzle state generated

---

## 🎮 Interactive Gameplay

Supported:

### Desktop

- Mouse drag and drop
- Tile swapping
- Position snapping

### Mobile

- Touch gestures
- Touch drag-and-drop controls
- Responsive interactions

Visual feedback included:

- Highlighted active puzzle piece
- Correctly positioned pieces marked visually
- Smooth transitions and animations

---

# Performance Tracking

## Timer

The application automatically:

- Starts timing when gameplay begins
- Updates time in real-time
- Displays results upon completion

Format:

MM:SS.T

---

## Move Counter

Tracks:

- Total moves made
- Puzzle efficiency
- Completion progress

---

## Completion Tracking

Displays:

- Correctly placed pieces
- Total pieces
- Progress percentage

---

# Win Detection System

The game automatically detects:

- Puzzle completion
- Correct arrangement of all tiles

After completion:

- Timer stops
- Results modal appears
- Performance statistics are shown

---

# Leaderboard System

Implemented using browser localStorage.

Stores:

- Date
- Completion time
- Total moves
- Puzzle difficulty

Displays:

- Top 5 Best Scores

This allows performance tracking across multiple sessions.

---

# User Interface

The dashboard includes:

✅ Modern glassmorphism design

✅ Dark futuristic theme

✅ Mobile responsive layout

✅ Smooth animations

✅ Interactive controls

✅ Leaderboard section

✅ Results overlay

---

# Game Result

## Difficulty

3 × 3

## Completion Time

00:24.4

## Total Moves

4

## Puzzle Status

🎉 Puzzle Solved Successfully

---

# Key Learnings

### Webcam Integration

Learned how browser APIs can access live camera feeds securely using:

- getUserMedia()
- Canvas API
- Image Capture Techniques

---

### Image Processing

Learned how captured images can be:

- Sliced dynamically
- Converted into puzzle tiles
- Reconstructed through user interactions

---

### Game Logic

Explored:

- Puzzle randomization
- Position validation
- Win detection algorithms
- Move tracking systems

---

### Local Storage

Implemented:

- Persistent leaderboard
- Best score tracking
- Browser-based data storage

---

### Responsive Development

Built a game that works across:

- Desktop
- Mobile
- Tablet

using modern CSS layouts and adaptive design.

---
# Conclusion

This project demonstrated how Claude can generate complete interactive applications using only prompts.

The AI Face Puzzle Game combined:

- Webcam APIs
- Image processing
- Puzzle algorithms
- Drag-and-drop interactions
- Local storage
- Responsive UI design

into a single self-contained HTML application.

The result was a fun and engaging browser-based game that transformed a user's own face into an interactive puzzle challenge.

---

Challenge Completed ✅

ABTalks 60-Day Claude Challenge – Day 20
