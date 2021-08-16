
# The best way to start with react
My best way to start project with react.js

Install Bootstrap with Node Sass:
```sh
npm install bootstrap node-sass react-router-dom
```

Install Reactstrap:
```sh
npm install --save reactstrap
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

------------------------------------------------------------------------------------

Another way
```sh
npm install --save-dev prettier eslint-config-prettier eslint-plugin-prettier
```

Package.json
```sh
  "eslintConfig": {
    "extends": [
      "react-app",
      "plugin:prettier/recommended"
    ]
  },
  "prettier": {
    "printWidth": 90,
    "bracketSpacing": false,
    "trailingComma": "es5"
  },
```

------------------------------------------------------------------------------------

NEXT.JS
```sh
npm install react-bootstrap@next bootstrap@5.0.2 sass
```

Image Optimization
```sh
npm install next-optimized-images
npm install --save next-compose-plugins
npm install imagemin-mozjpeg imagemin-optipng imagemin-svgo
```

.eslint.json
```sh
{
  "extends": "next/core-web-vitals",
  "rules": {
    "@next/next/no-img-element": "off"
  }
}
```

.eslint.json
```sh
{
  "extends": "next/core-web-vitals",
  "rules": {
    "@next/next/no-img-element": "off"
  }
}
```
