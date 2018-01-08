"browser-sync": "^2.2.3",
    "gulp": "^3.8.11",
    "gulp-autoprefixer": "^2.1.0",
    "gulp-imagemin": "^2.2.1",
    "gulp-minify-css": "^1.0.0",
    "gulp-rigger": "^0.5.8",
    "gulp-sass": "^1.3.3",
    "gulp-sourcemaps": "^1.5.0",
    "gulp-uglify": "^1.1.0",
    "gulp-watch": "^4.1.1",
    "imagemin-pngquant": "^4.0.0",
    "rimraf": "^2.3.1"
    
    
    
    Після інсталяції (npm i) виникає помилка Error: `libsass` bindings not found. Try reinstalling `node-sass`?
    Для вирішення проблеми потрібно зробити наступне:
    
    npm uninstall --save-dev gulp-sass
    
    npm install --save-dev gulp-sass@2
    