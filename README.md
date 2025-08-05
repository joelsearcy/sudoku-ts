# Sudoku TypeScript

A React TypeScript application for playing Sudoku puzzles.

## Features

- Interactive Sudoku game board
- Digit entry with popover interface
- Game state management with React Context
- Theme support
- Mock API for puzzle data
- Built with React, TypeScript, and Vite

## Getting Started

### Prerequisites

- Node.js 18 or higher
- npm

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

### Development

Start the development server:
```bash
npm run dev
```

The application will open at `http://localhost:5173`

### Building for Production

```bash
npm run build
```

### Testing

```bash
npm test
```

## Project Structure

```
src/
├── api/             # API client and mock data
├── assets/          # Static assets
├── components/      # Reusable React components
│   ├── DigitPopover.tsx
│   ├── SudokuBoard.tsx
│   └── SudokuCell.tsx
├── pages/           # Page-level components
│   └── SudokuGame.tsx
├── store/           # Context providers and state management
│   ├── GameContext.tsx
│   └── ThemeContext.tsx
├── types/           # TypeScript type definitions
├── App.tsx          # Main application component
└── main.tsx         # Application entry point
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm test` - Run tests
- `npm run lint` - Run ESLint

## Technologies Used

- **React** - UI framework
- **TypeScript** - Type safety
- **Vite** - Build tool and development server
- **ESLint** - Code linting
- **React Context** - State management

## Development Setup

This project uses:
- **Vite** for fast development and building
- **TypeScript** for type safety
- **ESLint** with TypeScript rules for code quality
- **React 18** with modern features
