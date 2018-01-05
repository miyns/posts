
https://miyns.github.io/posts/

## how to start jekyll
### create development dir
mkdir my-site
cd my-site

### install github-pages
bundle init
echo 'gem "github-pages"' >> Gemfile
bundle install

### init current dir for jekyll
bundle exec jekyll new -f .

### run serve
bundle exec jekyll s
