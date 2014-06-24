## Docker Manager

This plugin works with the Discourse docker image. It allows you to perform upgrades via the web UI and monitor activity in the container.

### Development Notes

The client application is built using [Ember App Kit](https://github.com/stefanpenner/ember-app-kit).

In development mode, using `grunt server` will proxy to your Discourse instance running on port 3000.
Just open up a browser to port 8000 and you're off to the races!

To create a compiled version for distribution, run `./compile_client.sh` to compile the site and
move it into the proper directories.
