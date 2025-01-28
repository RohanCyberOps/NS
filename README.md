# NativeScript Clicker App

A simple mobile application built with NativeScript that implements a fun clicker game. The app features a counter that starts at 42 and decrements with each tap, demonstrating basic NativeScript functionality with a clean UI powered by Tailwind CSS.

## Features

- Interactive tap counter starting at 42
- Dynamic message updates based on tap count
- Clean UI with Tailwind CSS styling
- Cross-platform compatibility (iOS and Android)

## Prerequisites

- Node.js
- NativeScript CLI
- iOS and/or Android development environment setup

## Getting Started

1. Clone the repository
2. Install dependencies:
```bash
npm install
```
3. Run the application:
```bash
ns preview
```

## Project Structure

- `/app` - Contains the main application code
  - `app-root.xml` - Root application layout
  - `main-page.xml` - Main page UI definition
  - `main-page.js` - Main page logic
  - `main-view-model.js` - View model with business logic
  - `app.css` - Global styles (Tailwind CSS)
  - `app.js` - Application entry point

## Technology Stack

- NativeScript 8.8.0
- Tailwind CSS 3.4.0
- NativeScript Tailwind integration

## Development

The application uses a simple MVVM pattern:
- The view is defined in `main-page.xml`
- The view model logic is in `main-view-model.js`
- Styling is handled through Tailwind CSS classes

## Building

To build for production:

For Android:
```bash
ns build android
```

For iOS:
```bash
ns build ios
```

## License

This project is licensed for public use.
