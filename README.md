# Typescript/React Web Application Toolchain

### **Package Management**
This project utilizes Npm for package management. For more information on Npm, please visit [https://www.npmjs.com/](https://www.npmjs.com/).

### **Files**
This toolchain configured to develop web applications using Typescript and React, using Babel and Webpack. The following files can be used to develop the web application:

**Components**
- Typescript (ts, tsx)
- Javascript (js)
- React (jsx)

**Styling**
- Sass (sass, scss)


### **Build Commands**
Build commands can be added in the *package.lock* file. Currently supported commands include:

- **npm run build**
    - Runs the webpack build of the project, putting project outputs in the */dist/* directory
- **npm run watch**
    - Runs the webpack build with the watch patameter, which will rebuild the project on saved changes
- **npm run start**
    - Starts the web development server on *http://localhost:3400*. This server will automatically rebuild the project and reload the page on saved changes

---

### Additional Resources
The following resources can be used to learn more about the components of this web application:

[Create React App](https://reactjs.org/docs/create-a-new-react-app.html#more-flexible-toolchains)

[Creating a Custom Toolchain](https://blog.usejournal.com/creating-a-react-app-from-scratch-f3c693b84658)

[Webpack - Getting Started](https://webpack.js.org/guides/getting-started/)

[Webpack - Typescript Documentation](https://webpack.js.org/guides/typescript/)

[Webpack - Sass Documentation](https://webpack.js.org/loaders/sass-loader/)

[Webpack - Hot Module Replacement](https://webpack.js.org/guides/hot-module-replacement/)

[Webpack - HTML Plugin](https://webpack.js.org/plugins/html-webpack-plugin/)