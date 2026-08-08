# Image Viewer

A dependency-free image viewer that runs entirely in the browser. It supports common browser image formats alongside DDS textures and is ready to deploy as a static GitHub Pages site.

## Supported formats

- PNG, JPEG, GIF, WebP, AVIF, and BMP (browser-native decoding)

- DXT1 / BC1
- DXT3 / BC2
- DXT5 / BC3
- ATI1 / BC4
- ATI2 / BC5
- Common uncompressed RGBA8, BGRA8, RGB565, and A8 DDS files
- R8, RG8, luminance, BGR8, ARGB1555, ARGB4444, RGB10A2, and RGBA16 files
- Mipmaps and cube-map faces

## GitHub Pages

GitHub Pages' branch deployer serves the repository root or `/docs`, so either move these three files to the repository root (or `/docs`), or configure a GitHub Actions Pages workflow that uploads `dds-viewer/` as the artifact. No server, build step, or upload API is required.

Files are read with the browser File API and never leave the tab.
