
# Spotify Clone

## Overview

This project is a Spotify Clone built using React and Tailwind CSS. The application mimics the basic functionality of the Spotify music streaming platform, allowing users to browse through albums, play songs, and interact with a music player. The purpose of this project is to practice React development, particularly with React Router, state management, and the implementation of a music player using the HTML5 `<audio>` element, along with Tailwind CSS for styling.




## Features

- Browse Music: View a selection of albums and songs.

- Music Player: Play, pause, and seek through songs.

- Responsive Design: Adapted for various screen sizes using Tailwind's responsive utilities.
- Routing: Navigate between different sections of the app using React Router.
- Custom Hooks: Reusable logic for managing the audio player state.
- Tailwind CSS: Fast and efficient styling with utility classes.
- useRef Hook: Manage and control the audio element without causing re-renders


## Project Structure



```bash
src/
│
├── assets/              # Contains music data and assets like images
├── components/          # Reusable UI components
├── context/             # React Context for managing player state
├── hooks/               # Custom hooks for reusable logic
├── pages/               # Pages corresponding to routes
├── App.js               # Main application component
├── index.js             # Entry point of the application
└── index.css            # Tailwind CSS configuration and custom styles

```
    
## Installation

Clone the Repository:

```bash
git clone https://github.com/Sumytth/spotify-clone.git
cd spotify-clone
```
    
Install Dependencies:
```bash
npm install
```
Run the Development Server:
```bash
npm run dev
```
## Usage
- Browse Songs: Navigate through the albums and select a song to play.
- Control Playback: Use the play/pause button, and drag the seek bar to skip to different parts of the song.
- Responsive Navigation: The app adapts to different screen sizes using Tailwind's responsive utilities for optimal viewing on desktops, tablets, and mobile devices.
## Technologies Used
- React: JavaScript library for building user interfaces.
- Tailwind CSS: Utility-first CSS framework for efficient styling.
- React Router: For handling navigation within the app.
- HTML5 <audio> element: For playing music tracks.
- Custom Hooks: Encapsulate reusable logic like managing the audio player state.
- useRef Hook: Manage DOM elements and persist values across renders without re-rendering.
## License
This project is open-source and available under the
[MIT](https://choosealicense.com/licenses/mit/)

