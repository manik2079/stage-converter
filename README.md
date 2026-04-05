# Stage Converter

A web-based video/media stage converter built with React and FFmpeg (WebAssembly).

## Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm (comes with Node.js)

## Installation

```bash
git clone https://github.com/manik2079/stage-converter.git
cd stage-converter
npm install
```

## Usage

### Development Server

```bash
npm run dev
```

Opens a local development server powered by [Vite](https://vitejs.dev/).

### Production Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Run Quality Benchmarks

```bash
npm run benchmark:quality
```

To generate a JSON and Markdown report:

```bash
npm run benchmark:quality:report
```

## Tech Stack

- **React 18** - UI framework
- **Vite** - Build tool and dev server
- **FFmpeg (WASM)** - Client-side media processing
- **Vercel Blob** - Blob storage integration
