# Technical Interview Documentation Collection

A collection of modern, interactive web pages for various technical interview documentation sets including JavaScript, Front-end, Terraform, React, and TypeScript.

## Overview

This repository contains documentation for technical interviews across multiple technologies. Each documentation set has its own interactive web interface with consistent styling, sidebar navigation, language toggling (Korean/English), and dynamic content loading.

## Documentation Sets

- **JavaScript Interview**: JavaScript interview questions and answers
- **Front-end Interview**: Front-end development interview questions and answers
- **Terraform**: Terraform infrastructure as code interview questions and answers
- **React Interview**: React framework interview questions and answers
- **TypeScript Interview**: TypeScript language interview questions and answers

## Features

- **Modern UI**: Clean, responsive design with technology-specific theming
- **Sidebar Navigation**: Automatically extracts and displays questions from markdown files
- **Language Toggle**: Switch between Korean and English versions
- **Document Part Selection**: Navigate between different parts of the documentation
- **Full-width Content**: Optimized layout for better readability
- **Proper Text Wrapping**: Enhanced handling of long comments and code blocks

## Usage

To view any documentation set locally:

1. Navigate to the specific documentation directory:
   ```
   cd [Documentation Directory]
   ```

2. Start a local HTTP server:
   ```
   python3 -m http.server [PORT]
   ```
   
   Recommended ports:
   - JavaScript: 8000
   - Front-end: 8001
   - Terraform: 8002
   - React: 8005
   - TypeScript: 8006

3. Open your browser and navigate to:
   ```
   http://localhost:[PORT]
   ```

## Structure

Each documentation set follows a similar structure:

- `index.html`: Main HTML file for the documentation viewer
- `styles.css`: CSS styling with technology-specific theming
- `app.js`: JavaScript functionality for dynamic content loading and navigation
- Markdown files: Content files in both Korean and English

## License

This project is for personal educational use.
