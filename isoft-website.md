# iSoft Apps Website
Company introduction website, portfolio website

| Source | Link |
| --- | --- |
| <code>GitHub</code> | https://github.com/ss-kenghong/isoft-web |
| <code>Staging Preview</code> | https://isoft-web.netlify.app/ |
| <code>Live</code> | isoft.sg |

## Environment
<!-- ```
.
└── [server]
    └── index.js
└── [client]
    ├── [src] - Development
    ├── [dist] - Staging
    └── [build] - Live
```         -->
- [server]
  - [index.js]
- [client]
  - [src] - Development
  - [dist] - Staging
  - [build] - Live

## Technical Stack

- [Node.js] - v14.x
- [Gulp.js] - v4.x
- [Express.js] - MongoDB
- Vanilla JS
- jQuery

## Animation

- Animated On Scroll Library - https://michalsnik.github.io/aos/
- LottieFiles - https://lottiefiles.com/


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

  `<link rel="stylesheet" href="assets/css/style-ver.min.css">` will be update to `<link rel="stylesheet" href="assets/css/style-1.0.2.min.css">`


