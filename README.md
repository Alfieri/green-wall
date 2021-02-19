# green-wall

## Dev

prepare development environment
- install nodejs
- install VS Code

run the app

```bash
npm i # just once
ionic serve
```

### Initial Bootstrap

```bash
ionic start green-wall tabs --type=angular --capacitor
# add bluetooth
npm install cordova-plugin-bluetooth-serial
npm install @ionic-native/bluetooth-serial
ionic cap sync
```
