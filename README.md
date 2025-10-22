# AI Smart Focus Camera

A React-based web application that uses MediaPipe for real-time face detection and tracking. Built with Vite, TypeScript, and Tailwind CSS.

## Features

- Real-time face detection using MediaPipe
- Camera access and video streaming
- Responsive UI with Shadcn/ui components
- TypeScript for type safety
- Modern React with hooks

## Getting Started

### Prerequisites

- Node.js (v18 or higher) or Bun
- A modern web browser with camera access

### Installation

1. Clone the repository:
```bash
git clone https://github.com/synexistech/ai-smart-camera.git
cd ai-smart-camera
```

2. Install dependencies:
```bash
bun install
# or
npm install
```

3. Start the development server:
```bash
bun run dev
# or
npm run dev
```

4. Open [http://localhost:8080](http://localhost:8080) in your browser.

## Usage

1. Allow camera access when prompted
2. The app will automatically detect faces in the video stream
3. Face detection results are displayed in real-time

## Tech Stack

- **Frontend**: React 18, TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS, Shadcn/ui
- **Face Detection**: MediaPipe Tasks Vision
- **Package Manager**: Bun (recommended) or npm

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
