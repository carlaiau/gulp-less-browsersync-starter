# Gulp + LESS + Browsersync for static websites

You need another package manager Gulp.

Steps to get started:

in terminal. This will install gulp globally
```
npm install --global gulp-cli

```

Once actually within this folder, install all the project specific dependencies
```
npm install
```
This will use the npm-shriinkwrap file to provide some backwards compatability with gulp 3.9.* and newer versions of node.
Once the npm install is use the command:

```
gulp
```

Gulp will listen for changes to LESS, automatically compile into CSS so you can see the changes instanlty in the browser.
It'll also listen to changes in .html files, but you'll notice a quick reload when these changes are made.

If you want to use something like UIKit you can just include the CSS and JS into the header of the index.html file
and play from there. Later on we can split the header into a layout component or something like that, or build properly, but this is a quick way of getting started.