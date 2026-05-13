# OptiPixel Pro | Advanced Local Image Studio

[![Live App](https://img.shields.io/badge/Live%20App-Online-success?style=for-the-badge&logo=github)](https://asr-ajay.github.io/optipixel/)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg?style=for-the-badge)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

**OptiPixel Pro** is a professional-grade, 100% private Progressive Web App (PWA) designed for high-precision image optimization and editing. Built with a "Privacy by Design" philosophy, it executes all processing locally in your browser using WebAssembly and AI, ensuring your sensitive media never touches a server.

---

## 🚀 Key Features

### 💎 Premium Design & UX
- **Glassmorphism Interface**: A modern, sleek, and high-contrast studio environment.
- **Micro-Animations**: Smooth transitions powered by Framer Motion for a premium feel.
- **Native Experience**: Fully installable as a Desktop or Mobile app via PWA support.
- **Responsive Layout**: Optimized for high-productivity desktop workflows and quick mobile edits.

### 🛡️ Absolute Privacy
- **100% Client-Side**: No uploads, no servers, no cloud storage. Total data sovereignty.
- **Local AI Processing**: Background removal and image analysis happen entirely on your machine.
- **Secure by Default**: Works offline once cached, ensuring no data leakage.

### 🛠️ Professional Toolkit
- **Smart Compression**: Optimize JPEG, PNG, and WebP with real-time quality previews.
- **Precision Cropping**: 8-point draggable selection with aspect ratio locking.
- **Advanced Conversion**: Seamlessly transcode between modern formats including **AVIF** and **GIF**.
- **Selective Pixelate**: Obscure sensitive areas with localized pixelation controls.
- **AI Background Removal**: High-precision segmentation powered by ONNX WebAssembly.
- **Studio Essentials**: Batch resizing, rotation, mirroring, and vintage filters.

---

## 🛠️ How it Works

1.  **Select Media**: Drag and drop your images or click the upload zone to begin.
2.  **Edit in Studio**: Use the sidebar tools to apply non-destructive edits (Crop, Resize, Filter).
3.  **Optimize**: Adjust compression levels or change formats to meet your requirements.
4.  **Instant Download**: Save your professionally processed image directly to your device.

---

## 💻 Tech Stack

- **Framework**: [React 19](https://react.dev/) & [Vite](https://vite.dev/)
- **Animation**: [Framer Motion](https://www.framer.com/motion/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **AI & Processing**: 
  - [ONNX Runtime Web](https://onnxruntime.ai/) for local AI execution.
  - [@imgly/background-removal](https://github.com/imgly/background-removal-js) for segmentation.
  - [jSquash](https://github.com/GoogleChromeLabs/jsquash) for AVIF/WASM-based transcoding.
- **PWA**: `vite-plugin-pwa` for offline capabilities and standalone installation.

---

## ⚖️ Legal & License

### Copyright
**Copyright © 2024 asr-ajay. All rights reserved.**  
No part of this project may be copied, modified, or redistributed without explicit written permission from the author.

### License
This work is licensed under a **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)**.
- **Attribution**: You must give appropriate credit.
- **Non-Commercial**: You may not use the material for commercial purposes.
- **No-Derivatives**: If you remix, transform, or build upon the material, you may not distribute the modified material.

For full legal terms, please refer to the [LICENSE](LICENSE) file.

---
*Developed with ❤️ for the Creative & Privacy Community.*
