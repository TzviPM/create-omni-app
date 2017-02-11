# eslint-config-omni-app

This package includes the shareable ESLint configuration used by [Create Omni App](https://github.com/Omniroot/create-omni-app).

Please refer to its documentation:

## Usage in Create Omni App Projects

The easiest way to use this configuration is with [Create Omni App](https://github.com/Omniroot/create-omni-app), which includes it by default. **You don’t need to install it separately in Create Omni App projects.**

## Usage Outside of Create Omni App

If you want to use this ESLint configuration in a project not built with Create Omni App, you can install it with following steps.

First, install this package, ESLint and the necessary plugins.

  ```sh
  npm install --save-dev eslint-config-omni-app babel-eslint@7.0.0 eslint@3.8.1 eslint-plugin-flowtype@2.21.0 eslint-plugin-import@2.0.1 eslint-plugin-jsx-a11y@2.2.3 eslint-plugin-react@6.4.1
  ```

Then create a file named `.eslintrc` with following contents in the root folder of your project:

  ```js
  {
    "extends": "omni-app"
  }
  ```

  That's it! You can override the settings from `eslint-config-omni-app` by editing the `.eslintrc` file. Learn more about [configuring ESLint](http://eslint.org/docs/user-guide/configuring) on the ESLint website.
