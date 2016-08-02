# bucharest-gold.github.io
Website for Bucharest Gold activitites

## Build the Site

    $ make

## Develop the Site

Write content in markdown. Open an issue if you want to write content
in some other format.

For styling, the site uses [Bootstrap CSS](http://getbootstrap.com) for styling
and layouts. Add additional styling and overrides to `src/css/site.css`. For
templates, we use [Jade](http://jade-lang.com/).

To build the site and run a simple web server, watching for changes to files.
Note: changes to layouts require a restart.

    $ make serve

## Publish the Site

The site is published when changes are pushed to the `gh-pages` branch.
Think of the `master` branch as the staging site. When you commit changes
to the `master` branch and push them to github, those changes can be shared
and reviewed by just browsing the github project at
https://github.com/wildfly-swarm/wildfly-swarm.io/. You won't see any styling
there, but this is good for proofreading and whatnot. When you are happy
with what's there, you can publish the site using

    $ make deploy
