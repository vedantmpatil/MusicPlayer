
# 🎵 Music Player Web App

A responsive web-based music player that allows users to browse playlists, play songs, navigate tracks, and access related YouTube videos. Designed for ease of use and smooth playback, it adapts seamlessly to various devices and screen sizes.

---

## 📆 Live Demo
Visit the deployed app: [https://musicplayer.pythonanywhere.com/](https://musicplayer.pythonanywhere.com/)

---

## 🔧 Features

- 🔊 **Playlist Selection**: Choose from multiple curated playlists.
- ▶️ **Song Playback**: Play songs directly in the browser.
- ⏭️ **Next Track Navigation**: Skip to the next song with ease.
- 🎧 **YouTube Links**: Click through to the song's associated YouTube video.
- 📱 **Responsive Design**: Enjoy a consistent experience across all screen sizes.

---

## 📄 Technologies Used

| Functionality       | Tech Stack             |
|---------------------|------------------------|
| Structure           | HTML                   |
| Styling             | CSS                    |
| Interactivity       | JavaScript             |
| Song Storage        | Static Files           |
| Backend (Optional)  | Python (Flask/app.py)  |
| Version Control     | Git                    |

---

## ▶️ Usage Guide

1. Open the app in a modern web browser or visit:
```

[https://musicplayer.pythonanywhere.com/](https://musicplayer.pythonanywhere.com/)

```
2. On the homepage, select a playlist from the available options.
3. Browse the list of songs displayed.
4. Click on a song to begin playback.
5. Use the player controls to skip to the next song or pause/resume.
6. Optionally, click the YouTube icon/link next to each song for the external video.

---

## 📁 Project Structure

```

sbvify/
├── static/
│   ├── covers/         # Album art or playlist covers
│   ├── css/            # Stylesheets
│   ├── js/             # Playback and UI logic
│   └── songs/          # Static MP3 files
├── template/
│   ├── index.html      # Homepage
│   ├── list.html       # Playlist page
│   ├── page1.html      # Additional playlist pages
│   └── card.html       # Song card layout
├── app.py              # Flask server (optional for hosting)
├── README.md

```

---

## 🚫 Limitations
- Does **not include authentication** or user-created playlists.
- Songs must be statically hosted in the `songs/` directory.
- Playback experience depends on browser compatibility.

---

## 🙌 Future Enhancements (Ideas)
- Playlist creation by users
- Search functionality
- Volume and shuffle controls
- Dark mode UI

---

## 📆 Live Demo
Visit the deployed app: [https://musicplayer.pythonanywhere.com/](https://musicplayer.pythonanywhere.com/)

---

## 👍 Credits
- Built using standard web technologies (HTML/CSS/JS)
- Deployed using [PythonAnywhere](https://www.pythonanywhere.com)

---

