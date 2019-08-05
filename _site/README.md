# <a href="https://ashcleave.github.io" target="_blank" >ashcleave.github.io</a>

### Getting Jekyll running locally
In the terminal:
```
gem install bundler
cd /project-directory-path
gco -b setup-jekyll
code Gemfile
```
Insert the following into `Gemfile`
```
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
```
Then back in the terminal:
```
bundle install
```

### Running Jekyll locally
`bundle exec jekyll serve`
