# electron-react-prototype

- `npm install -g create-react-app`
- `mkdir electron-react-prototype`
- `cd electron-react-prototype`
- `create-react-app .`
- `yarn add --dev electron`
- `package.json`
```
  },
  "main": "src/main.js",
  "scripts": {
    . . .
    "electron": "electron ."
  }
```
- `touch ./src/main.js`
- [electron-quick-start](https://github.com/electron/electron-quick-start)
- copy raw file of `src/main.js` from the quick-start repo into your `./src/main.js`
- Change `line 16` in `./src/main.js` to `mainWindow.loadURL('http://localhost:3000')` 

### Start two terminals

1st terminal
- `yarn start`

2nd terminal
- `yarn electron`