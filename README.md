# Online Binary Converter

![GitHub Release](https://img.shields.io/github/v/release/jisteven-epfl/binary-calc)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=flat&logo=vercel&logoColor=white)](https://binary-convertion.vercel.app/)

A simple and interactive web application to convert decimal numbers to 8-bit binary and vice versa.

🚀 **Live Demo:** [https://binary-convertion.vercel.app/](https://binary-convertion.vercel.app/)

## ✨ Features

- **Real-time Conversion**: Instantly converts decimal numbers to their 8-bit binary representation.
- **Interactive Bits**: Click on any bit to toggle it between 0 and 1, automatically updating the decimal value.
- **Input Validation**:
  - Ensures input is an integer.
  - Restricts input to the 0-255 range (8-bit limit).
  - Provides clear visual feedback for errors (e.g., empty input, out of range).
- **Responsive Design**: Clean and simple UI built with TailwindCSS.

## 🛠️ Tech Stack

This project was built using the following technologies:

- [React](https://react.dev/) - UI Library
- [TypeScript](https://www.typescriptlang.org/) - Type Safety
- [Vite](https://vitejs.dev/) - Build Tool
- [TailwindCSS](https://tailwindcss.com/) - Styling

## 🚀 Getting Started

Follow these steps to run the project locally on your machine.

### Prerequisites

- [Node.js](https://nodejs.org/) (Version 14 or higher recommended)
- npm (comes with Node.js)

### Installation

1. **Clone the repository** (if you haven't already):

    ```bash
    git clone <repository-url>
    cd binary-converter
    ```

2. **Install dependencies**:

    ```bash
    npm install
    ```

3. **Start the development server**:

    ```bash
    npm run dev
    ```

4. **Open in your browser**:
    Typically runs at `http://localhost:5173` (check the terminal output).

### Building for Production

To create an optimized build for deployment:

```bash
npm run build
```

The output will be in the `dist` directory.

## 💡 About This Project

This project is a **self-study initiative** to learn React web development. It focuses on understanding state management (decimal vs. binary representation) and handling user interactions in a React application. Feedback and suggestions are welcome!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
