# onBeat  
A Web-Based Music Experience


# PRESENTATION SLIDE
https://www.canva.com/design/DAG_AM3-nuc/HJDc_yylB1FK3LDLH4i6_A/edit?utm_content=DAG_AM3-nuc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

## Overview

**onBeat** is a web-based music player prototype designed to provide an interactive and visually engaging music listening experience.  
The project focuses on front-end development, user interface design, playlist handling, and accessibility features such as dark mode and color-blind mode.

This project is **not a final product** and is still under development. Some features may be incomplete or experimental.

---

## Project Objectives

- Build a simple music player using HTML, CSS, and JavaScript
- Implement playlist management without a backend
- Improve user experience through animations and visual feedback
- Support accessibility features:
  - Light / Dark mode
  - Color-blind friendly contrast
- Practice front-end logic using vanilla JavaScript

---

## Features

### Music Player
- Play, pause, next, and previous song controls
- Audio progress bar with seek functionality
- Repeat mode
- Floating playback controls
- Album artwork display
- Song title and artist display

### Lyrics Display
- Lyrics synced with playback time
- Dynamic lyric updates during playback
- Scrollable lyrics panel for long content

### Playlist Management
- Create custom playlists
- Add and remove songs
- Playlist cover image support
- Print playlist song list
- Playlist data stored using LocalStorage

### Search & Navigation
- Song search functionality
- Navigation between pages (Home, Playlist, About)

### UI & Animation
- Animated music visualizer bars
- Floating music-related animations
- Smooth hover effects and transitions
- Responsive layout for different screen sizes

### Accessibility & Personalization
- Light / Dark mode toggle
- Color-blind mode toggle with higher contrast
- User preferences saved using LocalStorage

---

## Technologies Used

- **HTML5** – Structure and layout
- **CSS3** – Styling, animations, and themes
- **JavaScript (Vanilla)** – Application logic and interactivity
- **Font Awesome** – Icons
- **Google Fonts (Poppins)** – Typography

No external JavaScript frameworks are used.

---

## Project Structure

onBeat/
├── index.html # Landing / entry page
├── main.html # Main music player interface
├── style.css # Styling, themes, and animations
├── script.js # Player logic and playlist handling
├── assets/ # Music files and album covers
└── README.md # Project documentation


---

## How It Works (Brief Explanation)

- Songs are defined as JavaScript objects inside `script.js`
- Each song contains:
  - title
  - artist
  - audio source
  - album cover
  - lyrics with timestamps
- During playback:
  - The audio element updates in real time
  - Lyrics synchronize based on playback time
  - The currently playing song is highlighted
- Playlist data is stored and retrieved using **LocalStorage**

---

## How to Run the Project

### Option 1: Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/ameenakeef233/onBeat.git

Open index.html using a web browser

Option 2: GitHub Pages

This project can be deployed as a static site using GitHub Pages by serving files from the main branch.