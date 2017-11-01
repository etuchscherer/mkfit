# mkfit
MKFit
This project was build around [spike](https://spike.readme.io/). Intended to be a dead simple static site, hosted on AWS / S3 / cloudfront.

## Installing

Clone the repo...

```
mkdir -p ~/Sites && cd ~/Sites
git clone git@github.com:etuchscherer/mkfit.git mkfit
$>npm i
```

## Building

Build assets with spike :: 

```
cd ~/Sites/mkfit 
$>spike compile       # one off build to a dist folder
$>spike watch         # serves w/ livereload
```

## Utilizes 

* [sugarml](https://github.com/reshape/sugarml) for templates 
* [sass](http://sass-lang.com/) for css
* [bootstrap 4](https://v4-alpha.getbootstrap.com/)
