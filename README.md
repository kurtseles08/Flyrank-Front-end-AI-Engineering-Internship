# Flyrank-Front-end-AI-Engineering-Internship

## Overview

This repository contains the front-end project developed as part of the Flyrank Front-End Internship.

## Tech Stack

- JavaScript
- React
- Vite
- HTML5
- CSS3
- Node.js
- npm

## Project Structure

This project follows the standard Vite + React layout:

```
Flyrank-Front-end-AI-Engineering-Internship/
├── public/              # Static assets served as-is
├── src/                 # Application source code
│   ├── assets/          # Images, fonts, and other imported assets
│   ├── components/      # Reusable React components
│   ├── App.jsx          # Root application component
│   ├── App.css          # Root component styles
│   └── main.jsx         # Application entry point
├── index.html           # HTML entry point for Vite
├── package.json         # Dependencies and npm scripts
├── package-lock.json    # Locked dependency versions
├── vite.config.js       # Vite configuration
├── .gitignore           # Git ignore rules
├── README.md            # Project documentation
└── LICENSE              # License information
```

### Directories

| Directory | Description |
|-----------|-------------|
| `public/` | Static files copied directly to the build output (e.g. favicons, robots.txt). Referenced by path from the root. |
| `src/` | Main application source code — React components, styles, and entry logic. |
| `src/assets/` | Assets imported into components (images, SVGs, fonts). Processed and optimized by Vite during build. |
| `src/components/` | Reusable UI components shared across pages or features. |

### Key Files

| File | Description |
|------|-------------|
| `index.html` | The single HTML page Vite uses as the app shell; loads `src/main.jsx`. |
| `src/main.jsx` | Bootstraps React and mounts the root component into the DOM. |
| `src/App.jsx` | Top-level React component that defines the main application layout. |
| `src/App.css` | Styles scoped to the root `App` component. |
| `package.json` | Lists project dependencies and defines npm scripts (`dev`, `build`, etc.). |
| `vite.config.js` | Vite build tool settings (plugins, dev server, aliases). |

## Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm (included with Node.js)

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/kurtseles08/Flyrank-Front-end-AI-Engineering-Internship.git
cd Flyrank-Front-end-AI-Engineering-Internship
npm install
```

## Running the Application

Start the development server:

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the app.

Build for production:

```bash
npm run build
```
