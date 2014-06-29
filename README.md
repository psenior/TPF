# TPF
---

This is a redesign of a website located at http://thepiaseckifoundation.org/.  They are a non-profit organization that I am currently taking a programming class with.  The original website is usable from desktop and laptop computers, but not from tablets or phones.  I took a free Bootstrap theme from http://coverstrap.com/previews/lighter.html and modified it.  This is a good little project for me to be able to show gratitude, to get more familiar with Bootstrap and with hosting static sites on Heroku.

Speaking of which, I have discovered that the old way of hosting static sites on Heroku via PHP (http://www.kennethreitz.org/essays/static-sites-on-heroku-cedar) no longer works.  I tried using Rack, following the instructions in this article (https://devcenter.heroku.com/articles/static-sites-ruby),  but ended up having problems with my glyphicons not displaying. Rack has worked for me on other sites (http://dfavinger.herokuapp.com).

I ended up using all the suggested tips from the following two articles in order to get this site online via PHP:

* http://michaeldroz.blogspot.com/2014/02/hosting-static-site-on-heroku-by.html
* http://stackoverflow.com/questions/23564500/is-it-possible-to-push-a-index-html-to-heroku

Only other thing I did was to put { } in my composer.json file as suggested by Heroku during deployment.

So far, I have tested this website on my Windows Phone 8.1 Developer Edition browser (IE?) and Firefox on my Amazon Kindle Fire.  It's definitely mobile friendly but my Windows Phone and the Javascript that zips from place to place on the page does not work so great all the time.

Future to-do's are to create web forms for some of the buttons.  They currently are linked to the original web site's forms.  

This is my second attempt at redesigning the site.  My first attempt can be seen at http://stark-fortress-2618.herokuapp.com/.  It is based on the free Bootstrap template from http://coverstrap.com/previews/strapped.html and is deployed to Heroku via Sinatra.  It started off as extra credit work in a class assignment from https://www.makeitwithcode.com/
