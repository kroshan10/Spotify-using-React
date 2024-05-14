# Music Player Application

This repository contains the source code for a music player application built with React. The application allows users to explore and play songs, manage playlists, and control playback.

## Components

### App Component

The `App` component serves as the main entry point for the application. It orchestrates the layout and integration of various components such as `Sidebar`, `Player`, and `Display`, and utilizes the `PlayerContext` to manage audio playback.

### Display Component

The `Display` component is responsible for rendering different content based on the current route. It utilizes React Router to handle routing and conditionally renders `DisplayHome` or `DisplayAlbum` components.

### DisplayAlbum Component

The `DisplayAlbum` component displays information about a specific album, including its name, description, and a list of songs. It utilizes React Router's `useParams` hook to retrieve the album ID from the URL and accesses album data from the `albumsData` asset.

### Navbar Component

The `Navbar` component provides navigation options and actions for the user. It includes buttons to explore premium features, install the app, and switch between music and podcast categories.

### Player Component

The `Player` component displays audio playback controls and song information. It utilizes the `PlayerContext` to access audio playback state and provides functionalities such as play, pause, previous, next, and seek.

### SongItem Component

The `SongItem` component represents an individual song item. It displays the song's name, image, and description and utilizes the `playWithId` function from the `PlayerContext` to play the song when clicked.

### PlayerContextProvider Component

The `PlayerContextProvider` component manages audio playback state and provides necessary context values for audio-related functionality. It includes functionalities for playing, pausing, seeking, and navigating between songs.

## Assets

The `assets` folder contains static assets such as images and icons used in the application.

## Usage

To run the application locally:

1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Start the development server using `npm start`.

## Author

[RK]
