# Sudoku TypeScript Project

This is a TypeScript React application for playing Sudoku.

## Getting Started

### Prerequisites
- Node.js 18+
- npm

### Development Setup

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Start development server**
   ```bash
   npm run dev
   ```

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
.
├── public/               # Static assets
├── src/                  # TypeScript React source code
│   ├── api/             # API client code
│   ├── assets/          # Assets (images, etc.)
│   ├── components/      # React components
│   ├── pages/           # Page components
│   ├── store/           # Context providers and state
│   ├── types/           # TypeScript type definitions
│   ├── App.tsx          # Main App component
│   └── main.tsx         # Entry point
├── package.json         # NPM dependencies and scripts
├── tsconfig.json        # TypeScript configuration
├── vite.config.ts       # Vite build configuration
└── eslint.config.js     # ESLint configuration
```

## Development Workflow

1. Start development server: `npm run dev`
2. Make changes and test in the browser
3. Run tests: `npm test`
4. Build for production: `npm run build`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm test` - Run tests
- `npm run lint` - Run ESLint
