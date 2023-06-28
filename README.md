# WebDev Starter

![webdev-starter](https://socialify.git.ci/devbytemehedi/webdev-starter/image?font=KoHo&forks=1&issues=1&name=1&pattern=Brick%20Wall&pulls=1&stargazers=1&theme=Auto)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Folder Structure](#folder-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Development Mode](#development-mode)
  - [Build Process](#build-process)
- [License](#license)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Introduction

WebDev Starter is a boilerplate project for frontend web development, providing a structured folder hierarchy and automation with Gulp. It is designed to help beginners and intermediate frontend developers kickstart their projects.

## Features

- Easy setup and configuration
- Well-organized folder structure for efficient project management
- Modular SCSS architecture using BEM methodology
- Automated build process with Gulp
- Minification and concatenation of CSS and JavaScript files
- Image optimization
- HTML minification
- Responsive design-ready
- Live reload for development
- Suitable for single-page and multi-page websites
- Version control (Git) and hosting (GitHub) compatibility
- Comprehensive documentation for easy reference and usage
- Licensed under the GPL 3.0 for open-source collaboration

## Folder Structure

Here is the folder structure of the project:

```js
webdev-starter
├── dist                        (Compiled and optimized files for production)
│   ├── assets                  (Static assets)
│   │   ├── favicons            (Favicon files)
│   │   ├── fonts               (Fonts directory)
│   │   └── images              (Optimized images)
│   ├── css                     (Minified CSS files)
│   ├── js                      (Minified and concatenated JavaScript files)
│   ├── pages                   (Minified HTML pages)
│   │   ├── about.html          (Minified about page)
│   │   ├── contact.html        (Minified contact page)
│   └── index.html              (Minified index.html)
├── src                         (Source files)
│   ├── assets                  (Static assets)
│   │   ├── favicons            (Favicons directory)
│   │   ├── fonts               (Fonts directory)
│   │   └── images              (Images directory)
│   ├── js                      (JavaScript files)
│   ├── scss                    (SCSS files)
│   ├── pages                   (HTML pages)
│   │   ├── about.min.html      (About page source)
│   │   ├── contact.min.html    (Contact page source)
│   └── index.html              (Main HTML file)
├── .gitattributes              (Git attributes file)
├── .gitignore                  (Git ignore file)
├── gulpfile.js                 (Gulp configuration file)
├── LICENSE                     (License information)
├── package-lock.json           (Package lock file)
├── package.json                (Package configuration file)
└── README.md                   (Project documentation)

```

<!-- ## Customization -->

## Getting Started

### Prerequisites

Before getting started with the project, make sure you have the following prerequisites installed on your system:

[![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://github.com/nodejs/node.git) [![NPM](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://github.com/npm/cli.git) [![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/) [![Windows Terminal](https://img.shields.io/badge/windows%20terminal-4D4D4D?style=for-the-badge&logo=windows%20terminal&logoColor=white)](https://aka.ms/terminal)

Follow the steps below to install them:

[![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://aka.ms/windows11) [![Terminal](https://img.shields.io/badge/windows%20terminal-4D4D4D?style=for-the-badge&logo=windows%20terminal&logoColor=white)](https://github.com/microsoft/terminal.git) [![Powershell](https://img.shields.io/badge/powershell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)](https://github.com/PowerShell/PowerShell.git)

```pwsh
winget install --id OpenJS.NodeJS Git.Git
```

This command will install the latest available versions of [NodeJS](https://nodejs.org/) and [Git](https://git-scm.com/) using [winget package manager](https://github.com/microsoft/winget-cli.git).

### Installation

**Clone repo or [download](https://github.com/devbytemehedi/webdev-starter/archive/refs/heads/main.zip) :**

```bash
git clone https://github.com/devbytemehedi/webdev-starter.git
```

**Navigate to the project directory :**

```bash
cd webdev-starter
```

**Install the required dependencies :**

```bash
npm install
```

## Usage

### Development Mode

During development, you can run the project in development mode with live reloading
Start the development server :

```bash
npm run dev
```

This will compile the SCSS to CSS, concatenate JavaScript files, optimize images, and launch a local development server. Any changes you make to the source files will automatically trigger a reload in the browser.

### Build Process

The project uses Gulp for automation. The build process includes:

- Compiling SCSS files to CSS and minifying them.
- Concatenating and minifying JavaScript files.
- Optimizing images for production.
- Minifying HTML files.
- Copying static assets to the dist directory.

To build the project for production, use the following command :

```bash
npm run build
```

This will compile and minify the SCSS and JavaScript files, optimize images, minify HTML files, and copy static assets to the `dist` directory. The final production-ready files will be available in the `dist` folder.

## License

This project is licensed under the GPL 3.0 License. See the [LICENSE](./LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests to suggest improvements or add new features.

## Acknowledgements

- [Gulp](https://gulpjs.com/) - A popular task runner for web development.
- [Sass](https://sass-lang.com/) - A CSS preprocessor that enhances the styling workflow.
- [BEM](https://en.bem.info/) - A methodology for writing maintainable and reusable CSS.
- [Node.js](https://nodejs.org/) - A JavaScript runtime environment for building server-side and networking applications.
