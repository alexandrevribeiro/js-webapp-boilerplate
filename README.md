# js-webapp-boilerplate

[![Travis Build Status][travis-image]][travis-url]
[![AppVeyor Build Status][appveyor-image]][appveyor-url]

A boilerplate for a JavaScript Web Application using:
* [express-app-runner][express-app-runner-url]
* Babel (using "ES6 preset")
* ESLint
* Travis CI configuration (for Node 7)
* AppVeyor CI configuration (for Node 7)

Using
---
To use this boilerplate you just need to clone it and copy what you think makes sense for your project.
    
    git clone https://github.com/alexandrevribeiro/js-webapp-boilerplate.git

Running the application
---
If you want to run the existing application (that's nothing else than a *Hello World*), you need to:
1. Install the dependencies: `npm install`
2. Start it: `npm start`

Linting
---
You can run ESLint in two ways:
1. Whenever you want to lint, by simply running the 'lint' script:    

    ```nodejs
    npm run lint
    ```
2. Watching the files, which besides linting them when running the command, it also lints the files every time you hit **Save**:

    ```nodejs
    npm run lint-watch
    ```

[express-app-runner-url]: https://npmjs.org/package/express-app-runner

[travis-url]: https://travis-ci.org/alexandrevribeiro/js-webapp-boilerplate
[travis-image]: https://img.shields.io/travis/alexandrevribeiro/js-webapp-boilerplate.svg?label=unix

[appveyor-url]: https://ci.appveyor.com/project/alexandrevribeiro/js-webapp-boilerplate
[appveyor-image]: https://img.shields.io/appveyor/ci/alexandrevribeiro/js-webapp-boilerplate.svg?label=windows