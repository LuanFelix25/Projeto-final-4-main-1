# Projeto Final 4

This project is a web application built using Vue.js and Vite. It is designed to provide a seamless user experience with a modern interface.

## Project Structure

- **.gitignore**: Specifies intentionally untracked files to ignore in the repository.
- **.nojekyll**: Prevents GitHub Pages from processing the site with Jekyll.
- **compose-up.cmd**: Command script for Windows to start the Docker Compose application.
- **compose.yml**: Defines the services, networks, and volumes for the Docker application.
- **index.html**: Main HTML file serving as the entry point for the web app.
- **package.json**: Contains metadata about the project, including dependencies and scripts.
- **published_index_after_fix.html**: Version of the index.html file after some fixes have been applied.
- **published_index.html**: Published version of the index.html file.
- **raw_index.html**: Raw version of the index.html file.
- **README.md**: Documentation and instructions for the project.
- **vite.config.js**: Configuration settings for Vite, a build tool for modern web projects.
- **.github/workflows/deploy.yml**: Defines the GitHub Actions workflow for deploying the application.
- **public/404.html**: Custom 404 error page for the application.
- **src/App.vue**: Root component of the application.
- **src/main.js**: Entry point for the Vue application, initializing the Vue instance.
- **src/assets/style.css**: Styles for the application.
- **src/router/index.js**: Sets up routing for the Vue application.
- **src/store/index.js**: Sets up the Vuex store for state management.
- **src/views/About.vue**: Vue component representing the About page.
- **src/views/Home.vue**: Vue component representing the Home page.

## Installation

To get started with this project, clone the repository and install the dependencies:

```bash
git clone <repository-url>
cd Projeto-final-4-main
npm install
```

## Usage

To run the application in development mode, use the following command:

```bash
npm run dev
```

## Deployment

For deployment, you can use the provided GitHub Actions workflow defined in `.github/workflows/deploy.yml`. Make sure to configure your deployment settings accordingly.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.