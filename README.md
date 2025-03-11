# MS Paint Clone

A nostalgic MS Paint clone built with Next.js 15, React 19, and Tailwind CSS. This web application recreates the classic Windows Paint experience with a modern tech stack.

![MS Paint Clone Screenshot](public/placeholder.jpg)

## Features

- **Classic Paint Interface**: Windows-style UI with a draggable window
- **Drawing Tools**: 
  - Brush tool for drawing
  - Eraser tool for corrections
- **Color Selection**: 28 color palette similar to the classic MS Paint
- **Canvas Operations**: Draw freely on a responsive canvas

## Tech Stack

- **Next.js 15**: React framework for production
- **React 19**: JavaScript library for building user interfaces
- **Tailwind CSS**: Utility-first CSS framework
- **TypeScript**: Static type checking
- **Radix UI**: Unstyled, accessible UI components
- **Shadcn UI**: A collection of re-usable components built with Tailwind CSS and Radix UI

## Getting Started

### Prerequisites

- Node.js 18.x or later
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ms-paint.git
   cd ms-paint
   ```

2. Install dependencies:
   ```bash
   npm install --legacy-peer-deps
   ```
   Note: The `--legacy-peer-deps` flag is used to bypass a dependency conflict between `date-fns` and `react-day-picker`.

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Usage

- **Select a Tool**: Click on the brush or eraser icons in the left toolbar
- **Choose a Color**: Select from the color palette at the bottom of the window
- **Draw**: Click and drag on the canvas to draw
- **Move the Window**: Drag the window title bar to reposition the paint application

## Project Structure

- `CorrectedPaintApp.tsx`: Main paint application component
- `app/`: Next.js application directory
  - `page.tsx`: Main page that renders the paint application
  - `layout.tsx`: Root layout component
  - `globals.css`: Global styles
- `components/`: Reusable UI components
  - `ui/`: UI components from Shadcn UI library
- `public/`: Static assets

## Building for Production

```bash
npm run build
```

Then, to start the production server:

```bash
npm start
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Inspired by Microsoft Paint
- Built with [Next.js](https://nextjs.org/)
- UI components from [Shadcn UI](https://ui.shadcn.com/)
