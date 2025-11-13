# Setup

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