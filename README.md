# Boilerplate for Chrome extension with angular browser action

Boilerplate for chrome extension using typescript and webpack with auto reload chrome extension plugin. Browser action made in angular.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

For use this app, you need to install node modules and run webpack.

Install modules:
```
npm install
```

Run webpack (development mode with watch and reload chrome extension plugin) and run angular watch (for browser action):
```
npm run nbuild-dev
npm run ng-build-dev
```

Run webpack (production mode) and angular production (for browser action):
```
npm run build-prod
npm run ng-build-prod
```

... and load unpacked extension from dist folder to your browser.


### TSLint

Fix file:
```
node_modules/tslint/bin/tslint --fix {file_with_path}
```
