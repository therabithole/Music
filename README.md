# Getting Started with IMBD Music App

This is a Fullstack IMDB project built using React + Node.js.

## Front-end

Front-end is built using React hooks.
Extensive use of SCSS and CSS-Grid for builtin css-support.
Beautiful / Extra fonts added: TiemposHeadline Series.
Extra Content: Music List + Music Header.
Icons are used as React SVG components and styles are changed with SCSS using inline-SVG and stroke prop.
Tiles use hook effects such as useCallBack to avoid re-rendering and performance optimisation.
Builtin checkbox to avoid usage of libraries.
Extensive use of reusable components and elements.
Proxy needs to be enabled to await and call getTiles and getTracks function.

### `Backend`

Backend is built using Node.js, MongoDB and usage of Multer GridfsStream // check folder middleware - multer.
Replace MongoDB url with MongoDB in the cloud Atlas account // db file.

// images are currently saved in static folders;
// Advanced options, images saved as multer gridFsStream
// advantage: no need of static array folder filtering (less code)

### `npm run build`

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

## Learn More

### Code Splitting

### Analyzing the Bundle Size

### Making a Progressive Web App

### Advanced Configuration
