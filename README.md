This is demo project for react-electron-app.

## React Electron App

Please follow below step for create react-eleactron-app.

#### 1. Create react app.

```
$ create-react-app <project-name>
```

#### 2. Install `electron`.

```
$ npm install --save-dev electron
```

#### 3. Add _electron-starter.js_

```
Create a electron-starter.js file inside *src* folder. Copy data from my electron-starter.js
```

#### 4. Modify _package.json_ file

Add main and homepage in package.json

```
 "main": "src/electron-starter.js",
 "homepage": "./",
```

Add new script for electron rub

```
"electron": "electron ."
```

#### 5. Build / Run project

```
$ npm run build
$ npm run electron
```
