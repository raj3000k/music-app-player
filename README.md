# Music Player App

![App Icon](lib/assets/launcher_icon.png)

A music player built with Flutter, using Riverpod for state management, Isar (Community Edition) as the database, and the `just_audio` package (with Waveform visualizer and background playback). This app serves as an experiment with various Flutter tools and libraries.

### Features:
- Create and manage playlists (edit names, images, songs).
- Add or remove songs with details (optional artist name) and supported audio formats: aac, amr, flac, mp3, mp4, m4a, wav, oog, opus.
- Play, pause, loop, shuffle, skip, and reorder songs.
- Sort playlists and songs by name, artist, and duration.
- Search for playlists and songs by name.
- Background playback with notification bar controls.

### Notes:
- Microphone permission is required for functionality; the app closes if permission is denied.
- Only specified audio formats are fully tested.
- Song paths are stored in the database; songs won’t play if files are deleted.
- Potential bugs may arise when interacting with playlists during playback.

### Key Learnings:
1. Isar Database
2. CustomPainter
3. StreamBuilder
4. Usage of just_audio, permission_handler, and path_provider
5. Importance of extensive planning for large apps
6. Type/Function Aliases
7. Package modification and usage via repo URLs
8. SearchDelegate
9. ReorderableListView for drag-and-drop
10. Sorting one list based on another

### Skills Reinforced:
1. Structuring projects
2. Writing utility functions
3. Implementing Riverpod state management
4. Managing app screens and navigation
5. Experimenting with Flutter widgets
