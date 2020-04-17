
# The best way to start with react
My best way to start project with react.js

Install Bootstrap with Node Sass:
```sh
npm install bootstrap node-sass react-router-dom
```

Install Reactstrap:
```sh
npm install --save reactstrap react react-dom
```

Install eslint and the team:
```sh
npm install eslint babel-eslint eslint-config-react-app eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react prettier --save-dev
```
.eslintrc file
```sh
{
  "extends": ["react-app", "plugin:jsx-a11y/recommended", "prettier/react"],
  "plugins": ["jsx-a11y", "prettier"],
  "rules": {
    "prettier/prettier": "off",
    "jsx-a11y/href-no-hash": [0],
    "radix": [0],
    "import/no-extraneous-dependencies": [0]
  }
}

```
