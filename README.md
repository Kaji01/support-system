#Starting with the project

Install nodejs
Install NPM
Install Git
Install Sass (3.4.2)
Install Compass (0.12.7)



sudo npm install bower gulp gulp-bower gulp-compass gulp-minify-css

First install: Will donwload Foundation framework
gulp install

Next:
gulp watch

Now just change sass rules in assets/scss/_settings.scss (see Foundation docs)
or assets/scss/incsub-support.scss. The styles will be compiled in assets/css

##Before releasing
This will minify the CSS

`gulp release`

Use git-archive-all to make the zip file.



