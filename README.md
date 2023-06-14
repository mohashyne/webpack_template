<div align="center">
 <img src="./src/assets/webpack.svg" alt="logo" width="140"  height="auto" />
  <h3><b>WebPack Template</b></h3>
</div>


# 📗 Table of Contents

- [📖 About the Project](#about-project)
- [💻 Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
- [🔧 Usage](#usage)
- [📁 Folder Structure](#folder-structure)
- [🤝 Contributing](#contributing)
- [📝 License](#license)

# 📖 <a name="about-project">About the Project</a>

This project provides a basic webpack configuration for building JavaScript applications. It includes the necessary plugins and loaders to bundle and optimize your code.

## 💻 Getting Started <a name="getting-started"></a>

To get started with this webpack configuration, follow these steps:

### Prerequisites

- Node.js (https://nodejs.org)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/mohashyne/webpack_template.git
    ```

   ### Install:

   ```sh
   cd webpack_template/
    npm install
    ```

   
   ### Install the dependencies:

   ```sh
   cd webpack_template/
    npm init -y
    npm install webpack webpack-cli --save-dev
    ```
    ### This is how the Package.json file will look like after installing the dependencies:
    
   ```sh
    {
     "name": "webpack-demo",
     "version": "1.0.0",
     "description": "",
  
      "private": true,
      "scripts": {
      "test": "echo \"Error: no test specified\" && exit 1"
      },
      "keywords": [],
      "author": "",
      "license": "MIT",
      "devDependencies": {
      "webpack": "^5.38.1",
      "webpack-cli": "^4.7.2"
      }
      }
    ```
   
    ### 🔧 Usage <a name="usage"></a>

     To use this webpack configuration, follow these steps:

    Place your JavaScript files in the src directory.

    Run the webpack build command:
       
        ```sh
         npm run build
        ```
    The bundled JavaScript file will be placed in the dist directory.

    ### 📁 Folder Structure <a name="folder-structure"></a>

    ```
    webpack_template/
    ├── dist/
        ├── bundle.js
    │   ├── index.html
    ├── node_modules/
    ├── src/
    │   ├── assets/
    │   │    ├── webpack.svg
    │   ├── styles/
    │   │   ├── main.scss
    │   ├── index.js
    ├── test.js
    ├── .gitignore
    ├── package-lock.json
     
    ├── package.json
    ├── README.md
    └── webpack.config.js
    ```

   ### Folder Structure Description <a name="folder-structure"></a>
    src/: Contains the source code files.
    dist/: Contains the bundled output files.
    webpack.config.js: The webpack configuration file.
    package.json: The npm package configuration file.

    🤝 Contributing <a name="contributing"></a>
    
    Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request.
    📝 License <a name="license"></a>



  ### 📝 License <a name="license"></a>


   
