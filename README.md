# MIT Scratch Clone 🎮

## 🌟 Live Demo
**[👉 TRY IT NOW ON VERCEL 👈](https://gulshan-mit-scratch-clone-gulshan-singhs-projects-b3fca0ca.vercel.app/)**

📹 **[Watch Demo Video](https://drive.google.com/file/d/1KRc_b02rd1FwHA6Cj0dxg-WDc99QwpFJ/view?usp=sharing)**

A lightweight, React-based visual coding platform inspired by MIT Scratch. Built for the Juspay Frontend Challenge.

![Project Screenshot](https://github.com/user-attachments/assets/578453c3-d00e-4914-973d-548b4b0d5472)

---

## 🚀 Features

### 🧱 Block-Based Programming
- Intuitive drag-and-drop interface
- Color-coded block categories (Motion, Looks, Control)
- Snap-together blocks that connect logically

### 🐱 Multiple Sprite Support
- Choose from various character sprites (Cat, Jerry, Mickey)
- Each sprite maintains its own code blocks
- Easy sprite switching with visual selector

### 🎬 Live Animation Engine
- Real-time execution of block sequences
- Visual feedback as code runs
- Interactive preview panel

### ⚡ Advanced Interactions
- Collision detection between sprites
- Speech and thought bubbles
- Customizable movement patterns

### 🎨 User-Friendly Interface
- Clean, intuitive layout inspired by Scratch
- Responsive design that works across devices
- Beginner-friendly with no coding experience required

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

## Technologies Used

- React
- Tailwind CSS
- Webpack
- ReScript (optional) 
