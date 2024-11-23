# Lyricify
Let's Lyricify your thoughts into musical words and make magic 🤩

## Basic Folder structure:-
```
Lyricify/
├── client/              # React Native app (mobile frontend)
│   ├── assets/          # Images, fonts, etc.
│   ├── components/      # Reusable UI components
│   ├── navigation/      # Navigation-related files
│   ├── screens/         # Individual screens (Home, Lyrics, Upload, etc.)
│   ├── services/        # API service handlers
│   ├── utils/           # Helper functions
│   ├── App.js           # Main entry point
│   └── package.json     # Dependencies
├── server/              # Backend API (Node.js)
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── server.js
│   ├── package.json
│   └── .env
└── README.md            # Documentation

```


## A detailed Folder structure we can follow:-
```
/project-root
│
├── /client                    # Frontend (React) code
│   ├── /public                # Public assets (e.g., index.html, images)
│   ├── /src                   # Main source folder
│   │   ├── /assets            # Static assets (e.g., images, fonts, icons)
│   │   ├── /components        # Reusable UI components
│   │   ├── /containers        # Components that connect to Redux or have logic
│   │   ├── /features          # Feature-based folders (e.g., auth, lyrics)
│   │   │   ├── /Auth          # Authentication-related components, logic
│   │   │   ├── /Lyrics        # Lyrics viewing, editing components
│   │   │   ├── /Notes         # Notes, formatting, and related components
│   │   ├── /hooks             # Custom React hooks
│   │   ├── /pages             # Page-level components (e.g., Home, Profile)
│   │   ├── /services          # API services and helper functions
│   │   ├── /store             # Redux store setup and slices
│   │   ├── /styles            # Global styles, theme, and CSS files
│   │   ├── App.js             # Main App component
│   │   ├── index.js           # Entry point for React
│   ├── package.json           # Client dependencies
│
├── /server                    # Backend (Node/Express) code
│   ├── /config                # Configuration files (e.g., database, JWT)
│   ├── /controllers           # Controller functions for each feature
│   ├── /middlewares           # Custom middleware (e.g., auth, error handling)
│   ├── /models                # Mongoose models (User, Lyrics, Notes)
│   ├── /routes                # API routes organized by feature
│   ├── /services              # Business logic (e.g., file upload, search)
│   ├── /utils                 # Utility functions (e.g., helpers, validators)
│   ├── app.js                 # Express app setup
│   ├── server.js              # Entry point for the server
│   ├── package.json           # Server dependencies
│
├── .env                       # Environment variables (not committed to version control)
├── .gitignore                 # Git ignore file
├── README.md                  # Project documentation```
