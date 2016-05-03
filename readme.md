# The HumanOps website

This is the public repo for the HumanOps website.

## Local setup

### Setup Jekyll

Setup the Gem bundle.

`bundle exec jekyll build --safe`

Update the bundle

`bundle update github-pages` or `gem update github-pages`

To run the Jekyll server and preview the site locally:

`bundle exec jekyll serve` or `./start.sh`

This will also run the watcher and update the static resources with any changes made.

Point your browser at the "Server Address" indicated in the output.

## Publishing

2) Merge master into the `gh-pages` branch and the live site will be automatically updated.


