#App REST built with PHP and Javascript

Talk about building a single page app using PHP and Javascript together, but separated.

This is the source from talk.

## Running the slides

The slides can be run locally from `file://` making development easy :)

## Running from a web server

If at some point you should need a web server, use [`serve.sh`](serve.sh). It will
launch a simple one and point your default browser to [`http://localhost:8000/template.html`](http://localhost:8000/template.html):

    $ cd backbone-hello-mundo-rest
    $ ./serve.sh

You can also specify a custom port:

    $ ./serve.sh 8080