# Node Package Manager

Node Package Manager is used to take bundles of code from other repositories or other developers and integrate them into our project's code.

## Installation NPM on Windows

1. Open the link: [https://docs.npmjs.com/downloading-and-installing-node-js-and-npm](https://github.com/coreybutler/nvm-windows/releases)
2. Select `nvm-setup.zip` then download it.
3. To verify the installation by running `npm -v` in your Command Prompt in administrator mode. And you can also check the version of Node.js by running `node -v`.

## Set up NPM

1. Create a folder `NPM`, and ensure that the file path of Command Prompt is already set to the file path where NPM is located.
2. Run `code .` to open your VS Code.
3. Run `npm init -y` to initialize a new project.

Note: You can change `"main": "index.js"` to `"main": "app.js"` in `package.json`, because use `"app.js"` for an application's entry point.

# Webpack

Webpack is used to bundle multiple JavaScript files into a single or multiple optimised output files for production.

## Installation Webpack on Windows

1. Run `npm i webpack webpack-cli webpack-dev-server html-webpack-plugin --save-dev` to install Webpack, Webpack CLI, Webpack Dev Server, and HTML Webpack Plugin.
2. Change `"test": "echo \"Error: no test specified\" && exit 1"` to `"build": "webpack", "serve": "webpack server", "deploy": "webpack --mode=production"` in `package.json`.
3. Create a JS file `webpack.config.js`, copy my `webpack.config.js` into yours.

# Typescript

TypeScript is a programming language that builds on JavaScript by adding static types.

## Installation Typescript on Windows

1. Run `npm i typescript ts-loader --save-dev`.
2. Create a JSON file `tsconfig.json`, copy my `tsconfig.json` into yours.

# WebGPU

WebGPU is a JavaScript API provided by a web browser that enables webpage scripts to efficiently utilize a device's graphics processing unit (GPU). This is achieved with the underlying Vulkan, Metal, or Direct3D 12 system APIs. On relevant devices, WebGPU is intended to supersede the older WebGL standard.

## Installation WebGPU on Windows

1. Run `npm i @webgpu/types`.

# Test 

1. Create a HTML file `index.html`, copy my `index.html` into yours.
2. Create a new folder `src` inside your project folder and copy my `app.ts` into your `app.ts`.
3. In Command Prompt, run `npm run serve`, click http://localhost:8080/
4. If everything's working you should see this page in your browser when you run the application:
   !(result.png)
