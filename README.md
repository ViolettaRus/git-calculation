# Calculator Application

A modern React-based calculator application built with TypeScript, Vite, and Ant Design.

## Features

- 🧮 Basic arithmetic operations (+, -, *, /, %)
- 🎨 Modern UI with Ant Design components
- 📱 Responsive design
- ⚡ Fast performance with Vite
- 🔧 TypeScript for type safety
- 📊 Real-time calculation display

## Tech Stack

- **React 18** - UI library
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **Ant Design** - UI component library
- **Lodash** - Utility functions

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ViolettaRus/git-calculation.git
cd git-calculation
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Project Structure

```
src/
├── components/
│   ├── Calculator/
│   │   ├── Calculator.tsx
│   │   └── index.tsx
│   └── CommonLayout/
│       ├── CommonLayout.tsx
│       └── index.ts
├── constants/
│   └── configTheme.ts
├── App.tsx
├── main.tsx
└── index.css
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Release Notes

### v1.0.0
- Initial release
- Complete calculator functionality
- Modern UI with Ant Design
- TypeScript support
- Responsive design
