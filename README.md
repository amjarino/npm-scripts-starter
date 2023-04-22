# npm-scripts-starter

A minimalistic starter kit for front-end development using only npm-scripts, with added support for Bootstrap, jQuery, Font Awesome, CSS animations, PWA, and icons. Includes scripts for Sass compilation, JavaScript bundling, image optimization, and file watching. Flexible and customizable using the package.json file. Perfect for developers who prefer a lightweight build system that relies only on the standard tools and features of npm, but also want to use popular front-end frameworks and libraries.

## Installation

To install this package, run the following command:

```bash
npm i npm-scripts-starter
```

## Dependencies

To install the dependencies, run the following command:

```
npm install
```

## Usage

To start using the scripts provided by this package, run the following command:

```
npm run start
```

This will run the script that concatenates and minifies CSS and JavaScript, minifies images, moves everything to a production folder, starts a live server, and watches for changes. You can customize this script by editing the `package.json` file.

## clone the repository

To get started, clone the repository and install the dependencies:

```
git clone https://github.com/your-username/npm-scripts-starter.git
cd npm-scripts-starter
npm install
```

## Usage

### Development

To start a development server with hot reloading, run:

```
npm run start
```

This will start a local development server at http://localhost:3000.

### Production

To create a production build, run:

```
npm run build
```

This will create a production-ready build of your project in the `dist` directory.

### Testing

To run tests, run:

```
npm run test
```

This will run any tests in the `tests` directory.

### Deploying

To deploy your project to GitHub Pages, run:

```
npm run deploy
```

This will create a production build and deploy it to the `gh-pages` branch of your GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use it as a starting point for your own projects.
