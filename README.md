My personal website based on the [academic pages](https://github.com/academicpages/academicpages.github.io) website template. Please see that repository for more details on setup and configuration.

## Setup:

1. If you want to host on github, fork repo and name it \<your username\>.github.io
1. Clone the repository
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `make serve` to continuously rebuild and serve at http://localhost:4000/
1. Alternately `make watch` to continuously rebuild without running a server, or just `make` to build once
1. If you are hosting the site from a non github server, just copy the contents of `_site` to that server after building. Alternately, you can overwrite the `make deploy` rule to deploy to that server after rebuilding
1. Run `make clean` to delete the built site


