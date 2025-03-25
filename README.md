# GetCertified - 3D Interactive Learning Platform

## Description

GetCertified is an interactive 3D web application built with React and Three.js, aimed at providing an immersive learning experience for certification preparation. The project demonstrates the integration of modern web technologies with 3D graphics to create engaging educational content.

## Technologies Used

- **React** - Frontend library for building user interfaces
- **TypeScript** - Static typing for JavaScript
- **Vite** - Next-generation frontend tooling
- **Three.js** - 3D graphics library
- **React Three Fiber** - React renderer for Three.js
- **React Three Drei** - Useful helpers for React Three Fiber

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (version 14.0 or higher)
- npm (usually comes with Node.js)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/subhamsingh123/GetCertified.git
    ```

2. Navigate to the project directory:
    ```bash
    cd GetCertified
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

## Development

To start the development server:

```bash
npm run dev
```

This will start the application in development mode. Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal).

## Building for Production

To create a production build:

```bash
npm run build
```

To preview the production build:

```bash
npm run preview
```

## Project Structure

```
src/
  ├── components/     # React components
  │   └── Scene.tsx  # Main Three.js scene
  ├── App.tsx        # Root component
  ├── main.tsx       # Entry point
  └── style.css      # Global styles
```

## Features

- Interactive 3D environment
- Responsive design
- Camera controls (orbit, pan, zoom)
- Basic lighting setup
- TypeScript support for better development experience

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Subham Singh - [GitHub Profile](https://github.com/subhamsingh123)

## Acknowledgments

- Three.js community
- React Three Fiber team
- Vite team
