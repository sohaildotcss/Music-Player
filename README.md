# Spotify Player

A modern Spotify-like music player built with React, Apollo Client, GraphQL, and Vite. This project showcases how to create a rich media player interface with powerful technologies, emphasizing performance and developer experience.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the App](#running-the-app)
  - [Linting](#linting)
  - [Building for Production](#building-for-production)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Demo

Check out a live demo of the project [here](#).

## Features

- Play, pause, and manage your playlist with a clean and intuitive UI.
- Real-time music data fetching using Apollo Client and GraphQL.
- Seamless audio playback with the `react-h5-audio-player` library.
- Responsive design with SASS, ensuring the app looks great on all devices.
- Fast and optimized development with Vite.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **Apollo Client**: A comprehensive state management library for JavaScript that enables you to manage both local and remote data with GraphQL.
- **GraphQL**: A query language for your API, providing a more efficient, powerful, and flexible alternative to REST.
- **Vite**: A next-generation front-end tooling that significantly improves the development experience.
- **SASS**: A CSS pre-processor that allows you to use features like variables, nested rules, and mixins in your CSS.

## Getting Started

### Prerequisites

Ensure you have the following installed on your local development environment:

- Node.js (version 14 or higher)
- npm or Yarn
- Git

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/spotify_players.git
   ```

2. Navigate to the project directory:

   ```bash
   cd spotify_players
   ```

3. Install the dependencies:

   ```bash
    npm install
   ```

   or

   ```bash
   yarn install
   ```

### Running the App

To start the development server:

```bash
npm run dev
```

or

```bash
yarn dev
```

The app should now be running on http://localhost:5173.

### Linting

To run ESLint:

```bash
npm run lint
```

or

```bash
yarn lint
```

This command checks for code quality issues and ensures consistency throughout the codebase.

### Building for Production

To build the app for production:

```bash
npm run build
```

or

```bash
yarn build
```

This command generates a production-ready build of the app in the `dist` directory.

## Folder Structure

The project structure is as follows:

```
spotify_players/
├── public/              # Static assets
├── src/                 # Source files
│   ├── components/      # Reusable components
│   ├── pages/           # Page components
│   ├── styles/          # SASS files
│   └── index.jsx        # Main entry point
├── .eslintrc.js         # ESLint configuration
├── vite.config.js       # Vite configuration
├── package.json         # Project metadata and dependencies
└── README.md            # Project documentation

```

## Contributing

Contributions are welcome! To contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).

After you have made your changes, open a pull request.

## License

This project is open source and available under the [MIT License](LICENSE).
