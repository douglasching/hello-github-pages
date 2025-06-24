# Sample GitHub Pages Site

## Initial set up

* Added Dev Container config: Ruby `mcr.microsoft.com/devcontainers/ruby:1-3.4-bullseye`
* Using VSCode open folder/project in dev container
* Jekyll: `gem install jekyll bundler`
* Did `jekyll new default-site` to get the start up jekyll files
    * Deleted folder `default-site` after taking the minimal set up needed like the `Gemfile`, `_config.yml` and `.gitignore`
* `bundle install`
* Add initial `index.md` following Jekyll standard with layout and title in meta data area at top.
* `bundle exec jekyll serve`
