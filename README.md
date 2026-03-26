# Page Replacement Algorithm Simulator

A frontend web application for simulating various page replacement algorithms used in operating systems memory management.

## Features

- **Five Page Replacement Algorithms:**
  - FIFO (First In First Out)
  - LRU (Least Recently Used)
  - OPT (Optimal)
  - LFU (Least Frequently Used)
  - Clock Algorithm

- **Interactive Visualization:**
  - Step-by-step simulation visualization
  - Real-time frame status display
  - Hit/Fault statistics
  - Detailed explanations for each step

## Tech Stack

- **React 19** - UI library
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Styling

## Project Structure

```
├── src/                    # Frontend source code
│   ├── components/         # React components
│   ├── utils/              # Utilities (simulator, API wrapper)
│   └── types.ts            # TypeScript types
└── package.json            # Dependencies and scripts
```

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Page-Replacement-Algorithm-Simulator
```

2. Install dependencies:
```bash
npm install
```

### Running the Application

Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or next available port).

### Building for Production

Build the application:
```bash
npm run build
```

Preview the production build:
```bash
npm run preview
```

## Usage

1. Select a page replacement algorithm from the dropdown
2. Enter a page request sequence (e.g., `1,2,3,4,1,2,5,1,2,3,4,5`)
3. Set the memory size (number of frames, 1-10)
4. Click "Start Simulation"
5. Navigate through steps to see detailed visualization

## Development

The project uses:
- **Vite** for frontend development with hot module replacement
- All simulations run entirely in the browser - no backend required!

## License

MIT
