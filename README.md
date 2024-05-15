# Text Editor Web Application

This is a web-based text editor application with the following features:

## Folder Structure

Upon opening the application in your editor, you will find a client-server folder structure.

## Running the Application

To start the application, run `npm run start` from the root directory. This command will initiate the backend and serve the client.

## Bundling JavaScript Files

When running the text editor application from the terminal, JavaScript files are bundled using webpack.

## Webpack Plugins

Webpack plugins generate an HTML file, service worker, and a manifest file.

## Next-Gen JavaScript Support

The text editor supports next-gen JavaScript, ensuring it functions in the browser without errors.

## IndexedDB Integration

Upon opening the text editor, IndexedDB immediately creates a database storage. Content entered is saved automatically, and upon reopening the editor, the content is retrieved from IndexedDB.

## Installation

Clicking the Install button allows you to download the web application as an icon on your desktop.

## Service Worker

When loading the web application, a service worker is registered using workbox. Static assets are pre-cached upon loading, including subsequent pages and static assets.

## Deployment

Proper build scripts for a webpack application are provided for deployment to Render.
