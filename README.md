# Electron Mountain

This repository contains **separate Electron applications**, each located in its own folder:

- **Screen Recorder** – A cross-platform desktop screen recording application
- **Image Resizer** – A simple desktop tool for resizing images

Each project is self-contained with its own setup and usage instructions.

---

## 📹 Screen Recorder

<img height="400" src="Screen Recorder/Screenshot.png">

### Overview

A versatile desktop screen recorder built with **Electron.js**.  
The application allows users to select a specific screen, window, or stream to record. It is compatible with **macOS, Windows, and Linux**, making it easy to capture screen activity across platforms.

### Setup

To run the Screen Recorder locally:

1. Navigate to the project folder:
   ```bash
   cd "Screen Recorder"
````

2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the app:

   ```bash
   npm start
   ```
4. Reload the app state:

   ```bash
   rs
   ```
5. Build the application:

   ```bash
   npm run make
   ```

---

## 🖼️ Image Resizer

<div style="display: flex; justify-content: center">
  <img src="Image Resizer/assets/screen.png" width="400" />
</div>

### Overview

An Electron application that allows you to select an image and easily change its width and/or height.

### Setup

To run the Image Resizer locally:

1. Navigate to the project folder:

   ```bash
   cd "Image Resizer"
   ```
2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the app:

   ```bash
   npm start
   ```

You can also use **Electronmon** to auto-reload during development:

```bash
npx electronmon .
```

### Packaging

There are multiple ways to package Electron apps.
[Eelectron Forge](https://www.electronforge.io/) is recommended, though packaging is not implemented in this project.

### Developer Mode

* When `NODE_ENV=development`, DevTools are enabled and open by default.
* When `NODE_ENV=production`, DevTools are disabled.

---

## 🤝 Contributing

While these are personal projects, contributions are welcome.
Feel free to open an issue or suggest improvements.

---

## 📄 License

This repository is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for details.
Just tell me 👍
```
