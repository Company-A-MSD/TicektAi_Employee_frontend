# TicketAi Employee Frontend

This is the Employee/Admin frontend for TicketAi, built with [React](https://react.dev/), [Vite](https://vitejs.dev/), and [Tailwind CSS](https://tailwindcss.com/). The project is configured for deployment on [Firebase Hosting](https://firebase.google.com/docs/hosting).

## Project Structure

```
.
├── .firebaserc
├── .gitignore
├── firebase.json
├── index.html
├── package.json
├── README.md
├── vite.config.mjs
├── public/
│   ├── favicon.ico
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── App.jsx
│   ├── App.test.js
│   ├── index.css
│   ├── index.jsx
│   ├── logo.svg
│   ├── reportWebVitals.js
│   └── setupTests.js
└── .github/
    └── workflows/
        ├── firebase-hosting-merge.yml
        └── firebase-hosting-pull-request.yml
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or newer recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd TicektAi_Employee_frontend
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

### Development

Start the development server:

```sh
npm start
```

- The app will be available at [http://localhost:3000](http://localhost:3000).
- The browser will open automatically.

### Building for Production

To build the app for production:

```sh
npm run build
```

- The optimized build will be output to the `build` directory.

### Testing

Run tests using:

```sh
npm test
```

- Uses [Jest](https://jestjs.io/) and [React Testing Library](https://testing-library.com/).

## Deployment

Deployment is configured for Firebase Hosting. See [firebase.json](firebase.json) and [vite.config.mjs](vite.config.mjs).

- On push to `main`, the app is automatically built and deployed via GitHub Actions ([.github/workflows/firebase-hosting-merge.yml](.github/workflows/firebase-hosting-merge.yml)).
- On pull requests, a preview is deployed ([.github/workflows/firebase-hosting-pull-request.yml](.github/workflows/firebase-hosting-pull-request.yml)).

## Technologies Used

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Firebase Hosting](https://firebase.google.com/docs/hosting)
- [Jest](https://jestjs.io/)
- [React Testing Library](https://testing-library.com/)

## License

This project is for educational purposes.

---

**Note:** For environment-specific settings, use `.env` files as needed
