# Image Viewer

A dependency-free image viewer that runs entirely in the browser. It opens common image formats and DDS files locally, with image inspection, comparison, and conversion tools built in.

## Features

- Open images by browsing or dragging them into the viewer
- Inspect dimensions, format, file size, transparency, and DDS metadata
- Pan, zoom, toggle the checkerboard background, and choose nearest or smooth scaling
- Compare two images with a draggable A/B split
- Browse DDS mip levels and cube-map faces
- Convert one image to PNG, WebP, or JPEG
- Batch-convert selected images into a ZIP archive
- Keep files local: images are read and converted in the browser, never uploaded

## Supported formats

- PNG, JPEG, GIF, WebP, AVIF, and BMP (browser-native decoding)
- DDS: DXT1 / BC1, DXT3 / BC2, DXT5 / BC3, ATI1 / BC4, ATI2 / BC5
- Common uncompressed DDS formats including RGBA8, BGRA8, RGB565, A8, R8, RG8, luminance, BGR8, ARGB1555, ARGB4444, RGB10A2, and RGBA16
- DDS mipmaps and cube-map faces

## Run or deploy

No build step or server is required. Open `index.html` in a modern browser, or publish this repository as a static site (for example, with GitHub Pages).
