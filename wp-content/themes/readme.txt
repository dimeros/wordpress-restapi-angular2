copy rest-api and sqlite plugin to wp-content plugin
Edit/Create the wp-config.php from the wp-config-sample. 
db.php from sqllite plugin inside to wp-content. Then install everything: no mysql anymore!! 


Creation of ng-theme (css and php) - > style.css and index.php

- Activation ng-theme from administration panel 
- Change permalinks from 'plain' to 'post name' from administration panel
- Create page pointing to app with default template the created app-template (it is created inside the ng-theme)

- Watch files inside ng-theme.... babel!!!
npm init

npm install --save-dev babel-core babel-preset-es2015 browserify gulp gulp-watch gulp-batch gulp-less gulp-rename gulp-uglify tsify vinyl-source-stream
npm install --save angular4 reflect-metadata rxjs zone.js