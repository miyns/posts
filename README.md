
https://miyns.github.io/posts/

## how to start jekyll
### create development dir
```sh
mkdir my-site
cd my-site
```
### install github-pages
```sh
bundle init
echo 'gem "github-pages"' >> Gemfile
bundle install
```
### init current dir for jekyll
```sh
bundle exec jekyll new -f .
```
### change vars in _config.yml
### run serve
```sh
bundle exec jekyll s
```
