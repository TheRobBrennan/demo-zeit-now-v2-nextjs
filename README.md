# Welcome
This project is intended to serve as a lightweight example for creating a [NextJS](https://nextjs.org) application with the [create-next-app](https://github.com/segmentio/create-next-app) tool for a project that can be deployed to [Zeit Now 2.0](https://zeit.co/now).

This demo has been based off the original tutorial created by Zeit at [https://github.com/zeit/now-examples/tree/master/nextjs](https://github.com/zeit/now-examples/tree/master/nextjs)

## Cheat sheet
```
$ npx create-next-app demo-zeit-now-v2-nextjs
$ cd demo-zeit-now-v2-nextjs/

// Step 1 - Create the NextJS app
// Create pages/index.js
// Create pages/about.js
// Create components/header.js
// Verify your app is running by running `npm run dev`

// Step 2 - Create `now.json` for deployment to Zeit Now v2
// Replace `demo-nextjs-nowv2` with your own project name (e.g. `my-next-demo`)

// Step 3 - Deploy to now
$ npm run deploy

> demo-zeit-now-v2-nextjs@ deploy /Users/rob/repos/demo-zeit-now-v2-nextjs
> now

> Deploying ~/repos/demo-zeit-now-v2-nextjs under therobbrennan
> Using project demo-nextjs-nowv2
> Synced 1 file (161B) [1s]
> https://demo-nextjs-nowv2-505c0b45f.now.sh [v2] [in clipboard] [2s]
┌ next.config.js        Ready               [2m]
├── λ about (1.57MB) [sfo1]
├── λ index (1.57MB) [sfo1]
├── _next/static/chunks/0.js (424B)
├── _next/static/chunks/0.js.map (99B)
├── _next/static/runtime/main-2992a07ed3e26f950054.js (19.74KB)
├── _next/static/runtime/webpack-42652fa8b82c329c0559.js (1.45KB)
├── _next/static/runtime/webpack.js (33.91KB)
├── _next/static/runtime/webpack.js.map (35.15KB)
├── _next/static/tLcll3KNJ9b9Tp6NST7Nb/pages/_app.js (2.53KB)
├── _next/static/tLcll3KNJ9b9Tp6NST7Nb/pages/_error.js (9.78KB)
├── _next/static/tLcll3KNJ9b9Tp6NST7Nb/pages/about.js (1.09KB)
├── _next/static/tLcll3KNJ9b9Tp6NST7Nb/pages/index.js (509B)
├── _next/static/webpack/0e21210685e1678946a6.hot-update.json (35B)
├── _next/static/webpack/ba5774594f449a1ee3b0.hot-update.json (35B)
├── _next/static/chunks/commons.7941a78b8e5c7626d555.js (186.54KB)
├── _next/static/development/pages/_error.js.map (185.23KB)
├── _next/static/development/pages/_error.js (235.73KB)
├── _next/static/development/pages/_app.js.map (285.48KB)
├── _next/static/development/pages/about.js.map (308.48KB)
├── _next/static/development/pages/index.js.map (307.81KB)
├── _next/static/development/pages/_app.js (329.57KB)
├── _next/static/development/pages/about.js (359.38KB)
├── _next/static/development/pages/index.js (355.84KB)
├── _next/static/development/dll/dll_724ae78efd21d9b28c3a.js (882.95KB)
├── _next/static/runtime/main.js.map (853.48KB)
├── _next/static/runtime/main.js (837.58KB)
└── static/favicon.ico (14.73KB)
> Success! Deployment ready [2m]

```