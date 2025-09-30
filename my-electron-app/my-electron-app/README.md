# My Electron App

A simple Electron application with hot reload for development.

## Prerequisites

- [Node.js](https://nodejs.org/) (which includes npm)

## Installation

1. Clone or download this project
2. Navigate to the project directory
3. Install dependencies:

```bash
npm install
```

## Running the App

To start the application:

```bash
npm start
```

The app window will open and display your application.

## Development Features

### Hot Reload

This project includes **hot reload** functionality via `electron-reloader`. This means:

- **Automatic reloading**: When you save changes to any `.js`, `.html`, or `.css` files, the app will automatically reload to reflect your changes
- **No manual restarts needed**: Just edit, save, and see your changes instantly
- **Development only**: Hot reload only runs in development mode and won't be included in production builds

### How to Use Hot Reload

1. Start the app with `npm start`
2. Keep the app window open
3. Edit any file in your project (e.g., `index.html`, `main.js`, styles)
4. Save the file
5. Watch the app automatically reload with your changes!

**Note**: If you see syntax errors during hot reload, it may be because the reloader caught your file mid-save. Just save again and it should recover.

## Project Structure

```
my-electron-app/
├── main.js          # Main process (app entry point)
├── index.html       # Renderer process (UI)
├── package.json     # Project configuration and dependencies
└── README.md        # This file
```

## Built With

- [Electron](https://www.electronjs.org/) - Framework for building desktop apps
- [electron-reloader](https://github.com/sindresorhus/electron-reloader) - Hot reload for development

## License

MIT

