# Oriol Mauri Guiu (CV) [![Build Status](https://travis-ci.org/maguri/cv.svg?branch=master)](https://travis-ci.org/maguri/cv)
Static web site deployed on Github Pages.

**Compile & Run the web in Github Pages**
#### Using [Travis CI](https://travis-ci.org/) & [GitHub Pages](https://pages.github.com/) ####

Automatic deploy after commit and push in GitHub

> **Steps:**

> - `(master) $ git commit -a -m "Commit comment"`
> - Travis CI build a container:
 - `hugo` #compile
 - `deploy.sh`
> - GitHub Pages serves the new commit (`gh-pages` branch)



#### Using [Hugo](https://gohugo.io/) ####

**Compile & Run the web in [localhost](http://localhost:1313)**
```
$ hugo -v
$ hugo server

Started building site
0 draft content
0 future content
10 pages created
0 non-page files copied
3 paginator pages created
2 tags created
0 categories created
in 112 ms
Watching for changes in /home/path/to/my/project/my-site/{data,content,layouts,static,themes}
Serving pages from memory
Web Server is available at http://localhost:1313/url/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```
