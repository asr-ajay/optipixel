# OptiPixel Pro - Production Build

This directory contains the optimized production build of **OptiPixel Pro**, a powerful, local-first browser-based image processing studio.

## Important Note for Deployment
Because OptiPixel Pro utilizes `SharedArrayBuffer` for high-performance multi-threaded AI processing (specifically for the Magic Background Removal tool), your web server **must** include the following HTTP security headers when serving these files:

```http
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
```

If these headers are not present on your production server, the AI tools will fall back to single-threaded mode (which is significantly slower) or may fail to initialize on some browsers.

## Project Info
- **Framework:** React + Vite
- **Core Technology:** HTML5 Canvas, ONNX WebAssembly, UTIF, AVIF Enc
- **Deployment:** Ready for static hosting (GitHub Pages, Vercel, Netlify, Nginx)

*All image processing occurs strictly locally inside the user's browser, guaranteeing total privacy.*
