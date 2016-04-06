## How to install

1. Clone it on your desktop
2. **File** -> **Import Settings**
3. import **webstorm_settings.jar** file
4. **WebStorm** -> **Preferences...** -> **Editor** -> **Code Style**
5. **Scheme** use **MoneyballCodeStyle**
6. Click **Apply**
6. Click **OK**

## How to use .eslintrc

### Installation
```bash
npm install eslint -g
```
```bash
npm install --save-dev eslint-config-airbnb eslint-plugin-react babel-eslint eslint
```
### Code Quality Tools
1. **WebStorm** -> **Preferences...**
2. **LanguageS & Frameworker** -> **JavaScript** -> **Code Quality Tools** -> **ESLint**
3. checked **Enable**
4. select **ESLint package** /usr/local/lib/node_modules/eslint
5. click **Apply**
6. click **OK**
7. add package.json **scripts** block, **yourESLintDirectory** substituting in your ESLint Directory, e.g. `eslint src`
```bash
"scripts": {
  "lint": "eslint yourESLintDirectory"
}
```
### Terminal use ESLint
```bash
npm run lint
```

![Running](http://www.gaojian.tv/files/default/2015/10-04/160917d4a798778830.jpg?6.6.6)