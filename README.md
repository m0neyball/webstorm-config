## How to install

1. Clone it on your desktop
2. **File** -> **Import Settings**
3. import **webstorm_settings.jar** file
4. **WebStorm** -> **Preferences...** -> **Editor** -> **Code Style**
5. **Scheme** use **MoneyballCodeStyle**
6. Click **Apply**
6. Click **OK**

## How to use .eslintrc

1. Installation
```bash
npm install eslint -g
```
```bash
npm install --save-dev eslint-config-airbnb eslint-plugin-react babel-eslint eslint
```
2. **WebStorm** -> **Preferences...**
3. **LanguageS & Frameworker** -> **JavaScript** -> **Code Quality Tools** -> **ESLint**
4. checked **Enable**
5. select **ESLint package** /usr/local/lib/node_modules/eslint
6. click **Apply**
7. click **OK**
8. add package.json **scripts** block
```bash
"scripts": {
  "lint": "eslint yourDirectory"
}
```
9. Terminal use ESLint
```bash
npm run lint
```

![Running](http://www.gaojian.tv/files/default/2015/10-04/160917d4a798778830.jpg?6.6.6)