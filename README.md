# Angular-Slickgrid Demos
## Multiple Demos of the [Angular-Slickgrid](https://github.com/ghiscoding/Angular-Slickgrid) library
#### All demos are made with the Angular-CLI

### Installation
Choose the theme and feature you want, they are separated into 2 theme (Bootstrap 3 or 4) and there's a demo with Custom Locales (without `ngx-translate`, fixed Locales) and the other demos are all with `ngx-translate` (dynamically switch language on the fly).

#### VScode
If you use Visual Studio Code, you can also run each of the demo through the multiple VSCode Tasks.

## Bootstrap 3 - with `ngx-translate`
Common Bootstrap 3 demo using `ngx-translate` that allows for using multiple languages (locales) and switch them on the fly.

##### Install and Start Demo
```bash
git clone https://github.com/ghiscoding/angular-slickgrid-demos
cd bootstrap3-demo-with-translate
npm install # OR yarn install
npm start # OR yarn start
```

##### Build Demo
```bash
npm run build # OR yarn run build
```

## Bootstrap 3 - with Custom Locales
This is the same as the Bootstrap 3 demo except that it uses custom Locales and does not require (neither use) `ngx-translate` and are with fixed Locales (meaning you cannot switch language on the fly). The Locales that were added for the demo (English/French), can be found under `src/app/locales`. You can use and define your own custom Locales via TypeScript file.

##### Install and Start Demo
```bash
git clone https://github.com/ghiscoding/angular-slickgrid-demos
cd bootstrap3-demo-with-locales
npm install # OR yarn install
npm start # OR yarn start
```

##### Build Demo
```bash
npm run build # OR yarn run build
```

## Bootstrap 4 - with `ngx-translate`
Common Bootstrap 4 demo using `ngx-translate` that allows for using multiple languages (locales) and switch them on the fly.

##### Install and Start Demo
```bash
git clone https://github.com/ghiscoding/angular-slickgrid-demos
cd bootstrap4-demo-with-translate
npm install # OR yarn install
npm start # OR yarn start
```

##### Build Demo
```bash
npm run build # OR yarn run build
```