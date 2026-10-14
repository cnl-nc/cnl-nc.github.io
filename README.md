
Initial setup on macOS:

```
brew install rbenv
rbenv init
rbenv install $(echo .ruby-version)

git clone git@github.com:cnl-nc/cnl-nc.github.io
cd cnl-nc.github.io
bundle install
```

Run:

```
bundle exec jekyll serve
```

To update members:

```
vim _data/members.yml

git add _data/members.yml
git commit -m 'commit message'
git push origin main
```
