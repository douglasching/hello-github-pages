# Sample GitHub Pages Site

## Initial set up

* Added Dev Container config: Ruby `mcr.microsoft.com/devcontainers/ruby:1-3.4-bullseye`
* Using VSCode open folder/project in dev container
* Jekyll: `gem install jekyll bundler`
* Did `jekyll new default-site` to get the start up jekyll files
    * Deleted folder `default-site` after taking the minimal set up needed like the `Gemfile`, `_config.yml` and `.gitignore`
* `bundle install`
* Add initial `index.md` following Jekyll conventions:
    ```markdown
    ---
    layout: default
    title: Home
    ---
    ```
* Start the site: `bundle exec jekyll serve`

## Set up from clean clone

* Using VSCode, open folder in Dev Container
* `bundle install`
    * Might need to do `gem install jekyll bundler`
* `bundle exec jekyll serve`

## Run from existing working copy

* `bundle install` to ensure gems are installed
* `bundle exec jekyll serve`
