# CivNet Splash Page

## Jekyll

Server can be run locally on port 4000 by running: 

```sh
bundle exec jekyll serve
```

While the server is running, saving changes in any of the source directories will automatically recompile `_site`. On that note, don't edit anything directly in the `_site` directory. It is the compiled static site, and will be overwritten.

Blog posts in the _posts directory must follow the same naming scheme. The urls are generated from the file name.

CSS/SASS should be added to the `_sass` directory. `css/main.scss' imports those files and they are compiled into `_site`.
