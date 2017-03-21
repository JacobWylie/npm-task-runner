# npm-task-runner

<a href="https://docs.npmjs.com/misc/scripts">npm scripts documentation</a>

<p>{</p>
<p>  "name": "dice_simulator_2015",</p>
<p>  "version": "1.0.0",</p>
<p>  "description": "",</p>
<p>  "scripts": {</p>
<p>    "test": "mocha",</p>
<p>    "clear-build": "rm build/*",</p>
<p>    "uglify": "node_modules/.bin/uglifyjs src/models/* src/frontend.js -m -c -o build/app.js",</p>
<p>    "copy-files": "cp src/*.html build/ & cp src/*.css build/",</p>
<p>    "build": "npm run clear-build && npm run copy-files && npm run uglify"</p>     
<p>  },</p>
<p>  "author": "Andrew Chalkley",</p>
<p>  "license": "MIT",</p>
<p>  "devDependencies": {</p>
<p>    "mocha": "^2.2.5",</p>
<p>    "uglify-js": "^2.4.23"</p>
<p>  }</p>
<p>}</p>