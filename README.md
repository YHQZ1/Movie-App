# Movie Explorer App

A modern React-based application to browse and manage your favorite movies. Built with a modular component structure, context-based state management, and clean UI separation using CSS modules.

## 🛠️ Project Structure

```
frontend/
├── public/                  # Static files (e.g., favicon, manifest)
├── src/                     # Source code
│   ├── assets/              # Images and static assets
│   │   └── react.svg
│   ├── components/          # Reusable components
│   │   ├── MovieCard.jsx
│   │   └── NavBar.jsx
│   ├── contexts/            # React Context for global state
│   │   └── MovieContext.jsx
│   ├── css/                 # Component-specific CSS styles
│   │   ├── Favorites.css
│   │   ├── Home.css
│   │   ├── MovieCard.css
│   │   └── Navbar.css
│   ├── pages/               # Page-level components
│   │   ├── Favorites.jsx
│   │   └── Home.jsx
│   ├── services/            # API calls and data services
│   │   └── api.js
│   ├── App.css              # Global app styles
│   ├── App.jsx              # Main App component
│   ├── index.css            # Global index styles
│   └── main.jsx             # Entry point of the application
├── .gitignore
├── eslint.config.js         # ESLint configuration
├── index.html               # Base HTML file
├── package.json             # Project metadata and dependencies
├── package-lock.json
├── README.md
└── vite.config.js           # Vite configuration
```

## 🔧 Features

- Movie cards with reusable design.
- Context API for managing favorite movies.
- Page routing for Home and Favorites.
- Clean and modular CSS organization.
- Efficient API management via service layer.
- Built with Vite for blazing-fast development.

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/movie-explorer.git
   cd movie-explorer/frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## 🧪 Linting

Ensure code quality and consistency:

```bash
npm run lint
```

## 🧭 Folder-by-Folder Overview

| Folder       | Purpose |
|--------------|---------|
| `components/`| Reusable UI components like `NavBar` and `MovieCard`. |
| `contexts/`  | Global state logic using `React Context API`. |
| `css/`       | Isolated styling for each component and page. |
| `pages/`     | Page-level components for routing. |
| `services/`  | API service functions. |

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

Made with React, Context API, and a passion for clean code.
