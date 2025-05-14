# Music App

**Music App** is a cross-platform music streaming application designed for music enthusiasts who want to enjoy high-quality audio, manage playlists, and explore trending tracks. Whether you're coding, commuting, or chilling, Music App offers a sleek and intuitive interface for discovering and listening to your favorite songs.


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Features

- Light/Dark mode toggle
- Live previews of music and playlists
- Fullscreen player mode
- Cross-platform support (Web, Android, iOS)
- Search and filter songs
- Playlist creation and management

## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |


## 🗺️ Roadmap

Here's the development roadmap for the Music App:

### Phase 1: Project Setup
- [x] Initialize React project with Vite
- [x] Install and configure Tailwind CSS
- [x] Set up basic folder structure and routing

### Phase 2: UI & Layout
- [x] Create reusable components (Navbar, Sidebar, Player)
- [x] Build responsive layouts with TailwindCSS
- [x] Design Home, Library, and Search pages

### Phase 3: Music Playback
- [x] Integrate audio player (HTML5 `<audio>` or package)
- [x] Add play, pause, skip, and volume controls
- [ ] Display current song info and playback progress

### Phase 4: Song Data & Search
- [x] Use static JSON or mock API for song data
- [ ] Implement dynamic search functionality
- [ ] Add filtering by genre/artist

### Phase 5: Playlists & Library
- [ ] Create playlist view and add/remove functionality
- [ ] Allow users to like/save songs to a personal library

### Phase 6: User Accounts (Optional)
- [ ] Add Firebase authentication (Login/Signup)
- [ ] Store user data and playlists in Firebase

### Phase 7: Deployment
- [ ] Optimize for production
- [ ] Deploy to Vercel or Netlify
- [ ] Add a custom domain (optional)


## Installation

Install my-project with npm

```bash
  npm install my-project
  cd my-project
```
    
## Authors

- [@ogotomelekh](https://www.github.com/ogoto99)


## Appendix

This app uses the Spotify Web API for fetching track data.
All user preferences (theme, playlists) are stored locally or synced via Firebase.
Future updates may include AI-based music recommendations and social sharing features.
