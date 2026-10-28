# [vite-angular-template][repo]

_also broken_

[repo]: https://github.com/sombriks/vite-angular-template

Minimal angular template using vite. [I wish it was parcel][orig], but it is
what it is.

[orig]: https://github.com/sombriks/parcel-angular-template

## Initial setup

```bash
# mkdir vite-angular-template; cd vite-angular-template
touch vite.config.ts tsconfig.json index.html
mkdir src
touch src/main.ts src/app.component.ts src/main.sass
npm i -D @angular/core @angular/common
npm i -D @angular/platform-browser @angular/platform-browser-dynamic
npm i -D @analogjs/vite-plugin-angular @angular/compiler-cli
npm i -D vite typescript sass zone.js
npm pkg set scripts.dev="vite"
npm pkg set scripts.build="tsc && vite build"
```
