# Setup
brew install hugo
hugo new site flmmartins.github.io
git submodule add https://github.com/tom2almighty/hugo-narrow.git themes/hugo-narrow
echo "theme = 'hugo-narrow'" >> hugo.toml
hugo server


## Deprecated -  Jekill 
Although this works, customization of theme proved to be hard

[How to](https://docs.github.com/en/pages/quickstart) create repo

[Install jekyl](https://jekyllrb.com/docs/installation/)
PS: Had to install ruby with SSL: 

```
ruby-install ruby 3.4.1 -- \
--with-openssl-dir="$(brew --prefix openssl@3)"
```

After installing jekyll:
1. Run:  `jekyll new --skip-bundle .`
2. Change _config.yaml and Gemfile by reading the comment lines
3. Run: `bundle install`
4. Put Gemfile.lock on gitignore

# Run locally
5. Run code locally `bundle exec jekyll serve`

# Deploy
Push to main