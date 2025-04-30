# Movie Search Application

A modern React application that allows users to search and discover movies using the TMDB API. Features real-time search, trending movies section, and search history tracking with Appwrite backend.

## Features

- 🔍 Real-time movie search with debouncing
- 📈 Trending movies section based on search popularity
- 🎬 Detailed movie information including ratings and release dates
- 💨 Fast and responsive user interface
- 🔄 Search history tracking
- 📱 Mobile-friendly design

## Tech Stack

- **Frontend:**
  - React 19
  - Vite (Build tool)
  - TailwindCSS (Styling)
  - react-use (Utility hooks)

- **Backend/Services:**
  - TMDB API (Movie data)
  - Appwrite (Backend as a Service)
    - Database for tracking search history
    - Real-time trending movies

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm
- Appwrite account
- TMDB API key

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd first-react-app
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env.local` file in the root directory:
```env
VITE_TMBD_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
```

4. Start the development server:
```bash
npm run dev
```

## Project Structure

```
first-react-app/
├── src/
│   ├── components/
│   │   ├── MovieCard.jsx
│   │   ├── Search.jsx
│   │   └── Spinner.jsx
│   ├── appwrite.js
│   ├── App.jsx
│   └── main.jsx
├── public/
└── package.json
```

## Development Commands

- `npm run dev` - Start development server
- `npm run build` - Create production build
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Environment Variables

| Variable | Description |
|----------|-------------|
| `VITE_TMBD_API_KEY` | TMDB API authentication key |
| `VITE_APPWRITE_PROJECT_ID` | Appwrite project identifier |
| `VITE_APPWRITE_DATABASE_ID` | Appwrite database identifier |
| `VITE_APPWRITE_COLLECTION_ID` | Appwrite collection identifier |


## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [TMDB](https://www.themoviedb.org/) for providing the movie data API
- [Appwrite](https://appwrite.io/) for the backend services
- [TailwindCSS](https://tailwindcss.com/) for the styling system
- This project was built following [React JS 19 Full Course 2025](https://www.youtube.com/watch?v=dCLhUialKPQ&t=3783s) by [JavaScript Mastery] on YouTube
