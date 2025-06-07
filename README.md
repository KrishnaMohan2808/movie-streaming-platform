# Movie Streaming Platform 

> **Work in Progress:**  
> This project is not yet complete. I am actively working on adding more features and improvements.

This is a **movie streaming platform: K-movies** built with **React** for the frontend and **Firebase** for user authentication. It uses **The Movie Database (TMDB) API** to fetch and display movie content.

---

##  Features

-  **User Authentication** using Firebase (Sign up, Login, Logout)
-  **Browse Popular Movies** from TMDB
-  **Movie Details Page** with overview, rating, and images
-  **Search Functionality** to look up specific titles
-  **Responsive UI** styled to resemble Netflix
-  **Protected Routes** – Users must be logged in to access the platform

---

##  Technologies Used

- **React.js** – Frontend
- **Firebase** – Authentication and backend
- **TMDB API** – Movie and show data
- **React Router** – Navigation between pages
- **CSS / Styled Components** – UI styling

---


##  Project Structure

/src
/components # Reusable UI elements (cards, navbar, etc.)
/pages # Pages (Login, Signup, Home, MovieDetails)
/firebase.js # Firebase config and auth setup
/api.js # TMDB API logic
App.js # Main app logic and routes
index.js # React DOM entry point
.env # Environment variables (not committed)

yaml
Copy
Edit

---

##  Getting Started

### Prerequisites

- Node.js & npm installed
- A Firebase project (for authentication)
- A TMDB account to get the API key

---

###  Firebase Setup

1. Go to [Firebase Console](https://console.firebase.google.com/) and create a new project.
2. Enable **Authentication** > Sign-in method > Enable **Email/Password**.
3. Create a **Web App** in Firebase and copy your config.

---

###  TMDB Setup

1. Go to [TMDB Developers](https://www.themoviedb.org/documentation/api).
2. Create an account and request an **API key**.

---

###  Installation Steps

1. Clone this repo:

   ```bash
   git clone https://github.com/your-username/movie-streaming-platform.git
   cd movie-streaming-platform
Install dependencies:

bash
Copy
Edit
npm install
Create a .env file in the root directory and add your credentials:

env
Copy
Edit
REACT_APP_TMDB_API_KEY=your_tmdb_api_key
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
Run the app:

bash
Copy
Edit
npm start
The app will open at http://localhost:3000

 How to Use
Go to the Signup page and create an account.

Log in to access the home page.

Browse and search for movies.

Click a movie to view detailed info.

Use the logout option when done.

🔮 Upcoming Features
🔖 Add to Watchlist (Firestore)

🎞️ Movie Trailers integration

⭐ User Ratings & Comments

🌐 Multi-language support

🚀 Deploy on Firebase Hosting



 Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

 License
This project is open-source and available under the MIT License.

 Acknowledgements
TMDB for movie data

Firebase for auth and backend

Inspired by the design of Netflix





# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
