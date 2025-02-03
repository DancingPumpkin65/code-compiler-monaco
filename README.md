# React Code Editor

This project is a web-based code editor built with React and Monaco Editor. It allows users to write, edit, and execute code snippets in various programming languages.

## Demo

[Demo](https://dancingpumpkin65.github.io/code-compiler-monaco/)

## Features

- **Code Editing**: Write and edit code using the Monaco Editor.
- **Language Selection**: Choose from multiple programming languages including JavaScript, TypeScript, Python, Java, C#, and PHP.
- **Code Execution**: Execute code snippets and view the output directly in the browser.
- **Theming**: Dark mode support using Chakra UI.

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/DancingPumpkin65/code-compiler-monaco.git
   cd code-compiler-monaco
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

### Running the Project

To start the development server, run:
   ```sh
   npm run dev
   ```
This will start the Vite development server and open the application in your default web browser.

### Building the Project

To build the project for production, run:
   ```sh
   npm run build
   ```
The built files will be output to the `dist` directory.

### Linting

To lint the project, run:
   ```sh
   npm run lint
   ```

## Usage

1. Select a programming language from the dropdown menu.
2. Write or edit the code in the editor.
3. Click the "Run Code" button to execute the code and view the output.

## Dependencies

- React
- Monaco Editor
- Chakra UI
- Axios