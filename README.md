# ang41923
Angular 16 Ionic 7 PWA with asset generator

> `npm i -g @ionic/cli@latest`

> `ionic start ng16ion7 tabs --type=angular`

> `cd ng16ion7`

> `npm i -g @angular/cli@next`

> `ng update @angular/core@next @angular-devkit/build-angular@next --force`

> `ng add @angular/pwa@next --force`

> `rm ./src/assets/icons/*.png (the angular logo icons)`

> `rm -rf node_modules`

> `npm i --force`

add custom app icon.png and splash.png to /src/assets

> `npm i @capacitor/assets --save-dev --force`

> `cd ./src/assets && npx @capacitor/assets generate --assetPath . && cd ../..`

edit manifest.webmanifest icon paths to use ../../assets/icons/*.webp

> `ionic build`

> `npx http-server-spa www ./index.html 8100`
