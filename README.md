# npm-task-runner

<a href="https://docs.npmjs.com/misc/scripts">npm scripts documentation</a>

run mocha: 

$npm test

uglifyjs:

in package.json

script:
"uglify": "node_modules/.bin/uglifyjs src/models/* src/frontend.js -m -c -o build/app.js"

then: $npm run uglify