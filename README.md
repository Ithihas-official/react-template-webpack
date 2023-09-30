# REACT TEMPLATE

This is a basic react-app template build using webpack. It provides a simple and ready-to-use setup for developing React applications with Webpack as the build tool. Whether you're new to React or looking for a minimalistic starting point, this template can help you get started quickly.

### Features

- React 18
- webpack 5
- Babel for transpiling JSX and ES6
- scss,CSS and style loading support
- eslint basic config
- Development and production build configurations

### Getting started

- #### Clone the repository:

```bash
git clone https://github.com/Ithihas-official/react-template-webpack.git
```

- #### Navigate to the project folder:

```bash
cd react-template-webpack
```

- #### Install dependencies:

```bash
npm install #for npm
yarn install #for yarn
pnpm install #for pnpm
```

- #### Start the development server

```bash
npm run dev
```

This will launch the development server at http://localhost:8080.

Start building your React application:

You can start building your React components and application in the src directory. The entry point for your application is src/App.jsx. You can create additional components in the src/components directory.

- #### Production build:
  When you're ready to deploy your application, you can create a production build using the following command:

```bash
npm run build
```

This will generate optimizied production-ready assests in the "dist" folder.

- #### Folder Structure
  The project structure looks like this:

```plaintext

react-template-webpack/
├── src/
│   │
│   ├── App.jsx
│   ├── index.js
│   └── ...
├── dist/
│   ├── index.html
│   ├── bundle.js
│   └── ...
├── babel.config.json
├── .eslintrc.js
├── .gitignore
├── package.json
├── webpack.common.js
├── webpack.dev.js
├── webpack.production.js
└── README.md

```

- " **src/** " : This is where your application source code resides. You'll primarily work within the components directory to create React components and the index.js file as the entry point.

- " **dist/** " : The output directory where the production-ready assets are generated after running the npm run build command.

- **babel.config.json** : Babel configuration file for transpiling JSX and ES6 code.

- **.eslintrc.js** : ESlint configuration file for code linting with the Airbnb style guide.

- **.gitignore** : Gitignore file to specify files and directories to ignore in version control.

- **package.json** : The project's configuration file that lists dependencies, scripts, and other project settings.

- **webpack.common.js** : Webpack configuration file that defines how your application is bundled and processed .
- **webpack.dev.js** : Webpack configuration file for development environment
- **webpack.production.js** : Webpack configuration file for production build
