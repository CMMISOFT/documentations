# iSoft Apps Website
Company introduction website, portfolio website

<strong>source:</strong> https://github.com/ss-kenghong/isoft-web
<strong>staging preview:</strong> https://isoft-web.netlify.app/
<strong>live:</strong> https://isoft.sg/

## Environment

- [server]
  - [index.js]
- [client]
  - [src] - Development
  - [dist] - Staging
  - [build] - Live

## Server Side

Installation:

```bash
cd <project-root>/server
npm install
```

Run:

```bash
npm start
```

## Cient Side

It is recommended to install `gulp-cli` globally, which helps initializing and previewing the website locally.

Installation:

```bash
cd <project-root>/client
npm install
npm install --global gulp-cli
```

<br />Development run: `gulp`

- to start serving the files in src directory.

<br />Staging run: `gulp dist`

- to build everything in dist directory.

<br />Production run: `gulp build`

- to build everything in build directory (with versioning).

  \*Build version will increase when run this command
  `client/src/assets/version/version.js`
