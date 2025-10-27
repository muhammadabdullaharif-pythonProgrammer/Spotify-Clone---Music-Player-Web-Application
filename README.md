# Spotify Clone - Music Player Web Application

A fully functional Spotify clone built with HTML, Tailwind CSS, and JavaScript that allows users to upload and play their music collection with a beautiful, responsive interface.

## 🚀 Features

### 🎵 Music Player
- **Full Audio Controls**: Play, pause, next, previous, shuffle, and repeat
- **Progress Bar**: Seek through songs with visual progress indicator
- **Volume Control**: Adjustable volume slider
- **Time Display**: Current time and total duration
- **Auto-play**: Automatically plays next song when current ends

### 📁 File Management
- **Folder Upload**: Upload entire music folders with directory selection
- **Metadata Reading**: Automatically reads ID3 tags for song information
- **Cover Art Display**: Shows album artwork from metadata
- **Smart Naming**: Extracts artist names from filenames if metadata unavailable

### 🔍 Search & Discovery
- **Real-time Search**: Filter songs by title or artist name
- **Trending Songs**: Grid layout for uploaded music
- **Popular Artists**: Showcase section with artist profiles
- **Recently Played**: Automatically tracks and displays recently played songs

### 💫 User Interface
- **Responsive Design**: Works on desktop and mobile devices
- **Dark Theme**: Spotify-inspired dark color scheme
- **Smooth Animations**: Hover effects and transitions
- **Custom Scrollbars**: Hidden scrollbars for cleaner look
- **Sticky Elements**: Fixed header and player bar

### ❤️ User Experience
- **Like System**: Heart button to favorite songs
- **Quick Access**: Shortcuts to liked songs and recently played
- **Playlist Sections**: "Made For You" and "Daily Mix" placeholders
- **Notifications**: Success messages for actions

## 🛠️ Technologies Used

- **Frontend**: HTML5, Tailwind CSS, JavaScript (ES6+)
- **Audio Processing**: Web Audio API, jsmediatags for metadata
- **Icons**: Custom SVG icons and emojis
- **Styling**: Custom CSS animations and transitions

## 📦 Installation

1. **Clone or Download** the project files
2. **No build process required** - it's a single HTML file with CDN dependencies
3. **Open** `index.html` in a modern web browser
4. **Start uploading** your music folder to begin using the player

### Browser Requirements
- Modern browser with ES6+ support
- File System Access API support (for folder upload)
- Audio tag support

## 🎯 Usage

### Uploading Music
1. Click the **"Choose Music Folder"** button in the sidebar
2. Select a folder containing your audio files
3. The app will automatically:
   - Read file metadata (title, artist, cover art)
   - Display songs in the "Trending Songs" grid
   - Extract artist names from filenames if needed

### Playing Music
1. **Click any song card** to start playing
2. Use the **player controls** at the bottom:
   - ⏮️ Previous song
   - ▶️/⏸️ Play/Pause
   - ⏭️ Next song
   - 🔀 Shuffle mode
   - 🔁 Repeat mode
3. **Adjust volume** with the volume slider
4. **Seek through songs** using the progress bar

### Searching & Filtering
- Use the **search bar** in the header to filter songs by title or artist
- Songs are filtered in real-time as you type

### Managing Favorites
- Click the **heart icon** ❤️ in the player bar to like/unlike the current song
- Liked songs are highlighted and can be accessed via "Liked Songs" in Quick Access

## 🎨 Customization

### Adding Your Own Images
Replace the placeholder images in the `image/` folder:
- `1.jpg`, `2.jpg` - Playlist covers
- Artist images for the "Popular Artists" section
- Fallback images for songs without cover art

### Modifying Colors
The color scheme uses Tailwind CSS classes. Key colors:
- Primary: `bg-green-500` (Spotify green)
- Background: `bg-black`
- Cards: `bg-zinc-900`
- Text: `text-white`, `text-gray-400`

### Adding Features
The modular JavaScript structure makes it easy to add:
- Playlist creation
- User accounts
- Online music streaming
- Social features

## 📁 Project Structure

```
spotify-clone/
│
├── index.html              # Main application file
├── image/                  # Image assets
│   ├── 1.jpg              # Playlist cover
│   ├── 2.jpg              # Playlist cover  
│   ├── ar_rhmaan.jpg      # A.R. Rahman artist image
│   ├── arijit-singh-1200.jpg
│   ├── atif-aslam.jpg
│   ├── jubin-nautiyals.jpg
│   ├── pritam.jpg
│   ├── shreya.jpg
│   └── Trending/          # Fallback song covers
│       ├── 2.jpg
│       ├── 3.jpg
│       ├── 4.jpg
│       ├── 5.jpg
│       └── 6.jpg
└── README.md              # This file
```

## 🔧 Technical Details

### Audio File Support
- Supports all browser-supported audio formats (MP3, WAV, OGG, etc.)
- Automatic metadata extraction using jsmediatags
- Fallback cover art system

### Performance Features
- Lazy loading of song data
- Efficient DOM updates
- Memory management with object URLs

### Browser Compatibility
- Chrome/Edge: Full support
- Firefox: Full support  
- Safari: Limited folder upload support
- Mobile browsers: Responsive but limited file access

## 🐛 Known Limitations

1. **File Access**: Requires modern browser with File System Access API
2. **Mobile Support**: Folder upload may not work on mobile devices
3. **Persistence**: No data persistence between sessions
4. **Large Libraries**: Performance may degrade with very large music collections

## 🚀 Future Enhancements

- [ ] Local storage for playlists and favorites
- [ ] Keyboard shortcuts support
- [ ] Equalizer and audio effects
- [ ] Lyrics display
- [ ] Podcast support
- [ ] Crossfade between songs
- [ ] Sleep timer
- [ ] Import from streaming services

## 📄 License

This project is for educational purposes. Please respect copyright laws when uploading music files.

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements!

## 📞 Support

If you encounter any issues or have questions:
1. Check browser compatibility
2. Ensure audio files are in supported formats
3. Verify folder upload permissions are granted

---

**Enjoy your music!** 🎧
