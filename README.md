
[Take me to the cyber-dojo home page](https://github.com/cyber-dojo/cyber-dojo).

- - - -

[![Build Status](https://travis-ci.org/cyber-dojo/start-points-languages.svg?branch=master)](https://travis-ci.org/cyber-dojo/start-points-languages)

Note: The languages and their test frameworks have
been moved from this one repo into separate repos in
https://github.com/cyber-dojo/start-points-languages
where Travis builds their docker image, tests their
start-point files, and pushes their docker image to
dockerhub.

The [languages_list](https://github.com/cyber-dojo/start-points-languages/blob/master/languages_list)
file contains one url-per-line for each repo that has been moved to
https://github.com/cyber-dojo/start-points-languages.

- - - -

Assuming the files in the repos specified in the list have the
[correct format](http://blog.cyber-dojo.org/2016/08/creating-your-own-start-points.html)
you create a languages start-point from the list as follows:

```
$ URL=https://github.com/cyber-dojo/start-points-languages/blob/master/languages_list
$ ./cyber-dojo start-point create olve --list=${URL}
$ ./cyber-dojo up --languages=olve
```

The [languages_list](https://github.com/cyber-dojo/start-points-languages/blob/master/languages_list)
file is the languages default. In other words the commands above are the same as:

```
$ ./cyber-dojo up
```

<img src="https://raw.githubusercontent.com/cyber-dojo/nginx/master/images/home_page_logo.png" alt="cyber-dojo yin/yang logo" width="50px" height="50px"/>

<img src="https://github.com/cyber-dojo/start-points-languages/blob/master/setup_default_practice.png" width="700px"/>
