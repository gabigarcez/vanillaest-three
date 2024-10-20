# Vanillaest Three

Minimal starter project using [THREE.js](https://threejs.org/) ES6 modules with [Vite](https://vitejs.dev/) for cleaner and modular code. It sets up a basic scene with a rotating cube to help you get started quickly.

## Features

- **Simple Setup**: Minimal configuration using Vite.
- **ES6 Modules**: Leverages modern JavaScript modules (ES6) for import/export.
- **Effortless Bundling**: Automatic bundling and optimization (minification and treeshaking) with Vite.
- **Three.js Integration**: Ready-to-go scene with a rotating cube.
- **Hot Module Replacement**: Instant updates during development.

## Project Structure

```
vanillaest-three/
├── .github
│   └── dependabot.yml
├── public
│   ├── favicon.ico
│   └── social-image.png
├── src/
│   ├── main.js
│   └── style.css
├── .gitignore
├── LICENSE
├── README.md
├── index.html
├── package-lock.json
└── package.json
```

- **`index.html`**: The main HTML file that featuring the main script and stylesheet.
- **`src/main.js`**: The JavaScript entry point that sets up the THREE.js scene using ES6 modules.
- **`src/style.css`**: Basic styles for the project.
- **`public/`**: Contains static assets like `favicon.ico` that are publicly accessible.
- **`.github/dependabot.yml`**: Configures automated dependency updates using Dependabot.
- **`package.json`**: Includes project dependencies and scripts.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) (v6 or higher)

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/vanillaest-three.git
cd vanillaest-three
```

Install the dependencies:

```bash
npm install
```

### Running the Development Server

Start the development server:

```bash
npm start
```

Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to see the rotating cube.

### Building for Production

To build the project for production:

```bash
npm run build
```

The optimized files will be in the `dist` folder.

### Previewing the Production Build

To preview the production build locally:

```bash
npm run preview
```

## Usage

Once the development server is running, a basic scene with a rotating green cube will be displayed. You can modify the `src/main.js` file to change the geometry, material, or camera setup to suit your needs. For example, you can experiment with different geometries by changing the `THREE.BoxGeometry()` to `THREE.SphereGeometry()` or other Three.js objects.

## Documentation

- [Three.js Documentation](https://threejs.org/docs/)
- [Vite Documentation](https://vitejs.dev/guide/)

## Contributing

Contributions are not welcome. Fork it and do whatever you want with it.

## License

This project is licensed under the [MIT License](LICENSE).
