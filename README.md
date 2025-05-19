# MIT Scratch Clone 🎮
🔗 **Live Demo**: [Click Here](https://gulshan-mit-scratch-clone-gulshan-singhs-projects-b3fca0ca.vercel.app/)

A lightweight, React-based visual coding platform inspired by MIT Scratch. Built for the Juspay Frontend Challenge.


---

## 🚀 Features

- 🧱 Drag-and-drop code blocks (Motion, Looks, Events)
- 🐱 Multiple sprite support (Cat, Jerry, Mickey)
- 🎬 Live animation preview with execution engine
- ⚡ Collision-based animation triggers
- 🎨 Beginner-friendly UI with modular components

---

## 🛠️ Tech Stack

- ReactJS + TailwindCSS  
- Webpack (Custom config)  
- Vercel (Deployment)

---

## 📦 Getting Started

```bash
git clone https://github.com/singhgulshan185/Gulshan-MIT_Scratch_Clone.git
cd Gulshan-MIT_Scratch_Clone
npm install
npm start
```

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