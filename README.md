# Project Setup
This is a basic project structure for any kind of application using Gulp build system.

## Clone this structure via command line.

### Git
    Create a new repository on command line:
    
        echo "# Repository-name" >> README.md
        git init
        git add README.md
        git commit -m "first commit"
        git remote add origin https://github.com/MarekJCK/Repository-name.git
        git push -u origin master
        
### NPM & Gulp
1.  You will need Node.js' package ecosystem, npm. So install [Node.js](https://nodejs.org/en/).
2. **Create package.json:**                          `$ npm init`
3.  **Install Gulp global:**                         `$ npm install --global gulp`  
4.  **Install Gulp as devDepencency:**               `$ npm install --save-dev gulp`
5.  **Install Normalize.css as Dependancy:**         `$ npm install --save normalize.css`

6. **Install other gulp dependencies:**
    ```
      Sass:        $ npm install gulp-sass --save-dev
      Minify-CSS:  $ npm install gulp-minify-css --save-dev
      Webserver:   $ npm install gulp-webserver --save-dev
      Watch:       $ npm install gulp-watch --save-dev
    ```
    **USE *sudo* IF NEEDED**

7. **Run gulp:**  `$ gulp`
