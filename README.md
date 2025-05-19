# Scratch-Style Programming Environment

A visual programming environment inspired by Scratch, built with React and Tailwind CSS.

## Features

- Drag-and-drop block-based programming
- Multiple sprite support with collision detection
- Motion, looks, and control blocks
- Visual feedback for collisions with sound effects
- Real-time execution of code blocks

## Collision Detection

This project includes a robust collision detection system:

- Sprites detect collisions with other sprites using AABB (Axis-Aligned Bounding Box) collision detection
- Visual feedback includes:
  - Red ring around colliding sprites
  - Shake animation
  - "COLLISION!" text overlay
  - Sound effect
- Collision events are logged to the console for debugging

## Debugging Collisions

To debug collision issues:
1. Open your browser's developer console
2. Look for logs with "COLLISION DETECTED!" in red
3. Collision logs include sprite positions, bounding boxes, and distances
4. State updates are also logged when collisions occur

## Development

### Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

### Project Structure

- `src/components/` - React components
- `src/components/utils/` - Utility functions including collision detection
- `src/Assets/` - Images and other assets

## License

This project is open source and available under the MIT License.
