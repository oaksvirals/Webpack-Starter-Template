# Webpack Starter Template

## Description
This is my personal Webpack starter template configured with essential loaders and plugins. It's set up to help me kickstart my JavaScript projects quickly without having to configure everything from scratch. It includes configurations for processing CSS, images, fonts, and HTML.

## Prerequisites
Make sure you have Node.js installed on your system (https://nodejs.org/).

## Installation
To use this template for a new project, follow these steps:

1. Clone the repository:
git clone https://github.com/oaksvirals/webpack-starter.git your-new-project-name

2. Navigate into your new project directory:
cd your-new-project-name

3. Install the necessary dependencies:
npm install

## Usage

### Development
To start the development server:
npm run dev

This command will start the Webpack development server on port 3000. You can view your application at http://localhost:3000. The server provides hot reloading and source maps for better development experience.

### Building for Production

To build your application for production:
npm run build

This command will bundle your scripts, styles, and assets into the dist directory with content hash in filenames for caching purposes, ready for deployment.

## Customization

Webpack Configuration: The configuration file is located at webpack.config.js. It's set up for development mode with source maps, a development server, and rules for processing CSS, images, and fonts.

HTMLWebpackPlugin: This is configured to use 'src/template.html' as a template for the generated 'index.html' in the dist directory.

CSS: CSS files are processed with style-loader and css-loader.

Images and Fonts: The config includes loaders for handling image files (.png, .svg, .jpg, .jpeg, .gif) and font files (.woff, .woff2, .eot, .ttf, .otf), treating them as assets/resources.

Feel free to add or modify loaders and plugins as per your project needs.

## Common Issues and Troubleshooting

If you encounter any issues with missing dependencies or errors during the build process, try removing the node_modules directory and reinstalling the dependencies:

rm -rf node_modules
npm install

## Notes to Future Self

Keep your Node.js and npm updated to the latest stable versions.

Regularly check for updates to dependencies to benefit from performance improvements and new features.

If you find useful resources or learn new tricks related to Webpack or JavaScript, consider updating this README with those insights.