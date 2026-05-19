# {
  "name": "3d-basketball-game",
  "version": "1.0.0",
  "description": "3D Online Basketball Game with Full Customization",
  "main": "src/index.js",
  "scripts": {
    "dev": "webpack serve --mode development",
    "build": "webpack --mode production",
    "start": "npm run dev"
  },
  "dependencies": {
    "three": "^r128",
    "cannon-es": "^0.20.0",
    "howler": "^2.2.3",
    "socket.io-client": "^4.5.4"
  },
  "devDependencies": {
    "webpack": "^5.88.0",
    "webpack-cli": "^5.1.4",
    "webpack-dev-server": "^4.15.1",
    "babel-loader": "^9.1.3",
    "@babel/core": "^7.23.0",
    "@babel/preset-env": "^7.23.0"
  }
}
