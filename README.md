# Scratch Starter Project

A Scratch-like block programming interface built with React and webpack.

## Features

- Drag-and-drop block programming interface
- Multiple sprite support
- Visual execution of code blocks
- Collision detection between sprites
- Custom block types for movement, appearance, and control flow

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- pnpm (recommended) or npm

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/singhgulshan185/testinuploadfinal.git
   cd testinuploadfinal
   ```

2. Install dependencies with pnpm (recommended):
   ```
   # Install pnpm if you don't have it
   npm install -g pnpm
   
   # Install project dependencies
   pnpm install
   ```
   
   Or if using npm (may require additional troubleshooting):
   ```
   npm install
   ```

3. Start the development server:
   ```
   pnpm start
   ```
   
   Or with npm:
   ```
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3001`

## Troubleshooting

If you encounter issues with missing modules like babel-loader:

1. Remove node_modules directory:
   ```
   rm -rf node_modules
   ```
   
2. Reinstall with pnpm:
   ```
   pnpm install
   ```

3. If port 3001 is already in use:
   ```
   # Find the process using port 3001
   lsof -i :3001
   
   # Kill the process (replace PID with the actual process ID)
   kill -9 PID
   ```

## Project Structure

- `src/` - Source code
  - `components/` - React components
  - `Assets/` - Images and other assets
- `public/` - Static files
- `webpack.*.js` - Webpack configuration files

## Technologies Used

- React
- Tailwind CSS
- Webpack
- ReScript (optional) 