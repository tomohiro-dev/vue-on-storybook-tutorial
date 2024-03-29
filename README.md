vue:3.0

1.  **Dev commnand.**

    ```shell
    # Run the test runner (Jest) in a terminal:
    yarn test:unit

    # Start the component explorer on port 6006:
    yarn storybook

    # Run the frontend app proper on port 8080:
    yarn serve
    ```
    


<p align="center">
  <a href="https://www.chromatic.com/">
    <img alt="Chromatic" src="https://avatars2.githubusercontent.com/u/24584319?s=200&v=4" width="60" />
  </a>
</p>

<h1 align="center">
  Chromatic's Intro to Storybook Vue template
</h1>

This template ships with the main Vue and Storybook configuration files you'll need to get up and running fast.

## 🚅  Quick start

1.  **Create the application.**

    Use [degit](https://github.com/Rich-Harris/degit) to get this template.

    ```shell
    # Clone the template
    npx degit chromaui/intro-storybook-vue-template taskbox
    ```

1.  **Install the dependencies.**

    Navigate into your new site’s directory and install the necessary dependencies.

    ```shell
    # Navigate to the directory
    cd taskbox/

    # Install the dependencies
    yarn
    ```

1.  **Open the source code and start editing!**

    Open the `taskbox` directory in your code editor of choice and building your first component!

1.  **Browse your stories!**

    Run `yarn storybook` to see your component's stories at `http://localhost:6006`

## 🔎 What's inside?

A quick look at the top-level files and directories included with this template.

    .
    ├── .storybook
    ├── node_modules
    ├── public
    ├── src
    ├── tests
    ├── .gitignore
    ├── babel.config.js
    ├── jest.config.js
    ├── LICENSE
    ├── yarn.lock
    ├── package.json
    └── README.md


1.  **`.storybook`**: This directory contains Storybook's [configuration](https://storybook.js.org/docs/react/configure/overview) files.

2.  **`node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages).

3.  **`public`**: This directory will contain the development and production build of the site.

4.  **`src`**: This directory will contain all of the code related to what you will see on your application.

5.  **`tests`**: This directory will contain all of unit test files for your project.

6.  **`.gitignore`**: This file tells git which files it should not track or maintain during the development process of your project.

7.  **`.babel.config.js`**: This file tells [babel](https://babeljs.io/) how to transpile the application's code.

8.  **`jest.config.js`**: This is a configuration file for [Jest](https://jestjs.io/).

9. **`LICENSE`**: The template is licensed under the MIT licence.

10. **`package.json`**: Standard manifest file for Node.js projects, which typically includes project specific metadata (such as the project's name, the author among other information). It's based on this file that npm will know which packages are necessary to the project.

11. **`yarn.lock`**: This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(Do not change it manually).**

12. **`README.md`**: A text file containing useful reference information about the project.

## Contribute

If you encounter an issue with the template, we encourage you to open an issue in this template's repository.

## Learning Storybook

1. Read our introductory tutorial at [Learn Storybook](https://storybook.js.org/tutorials/intro-to-storybook/vue/en/get-started/).
2. Learn how to transform your component libraries into design systems in our [Design Systems for Developers](https://storybook.js.org/tutorials/design-systems-for-developers/) tutorial.
2. See our official documentation at [Storybook](https://storybook.js.org/).
