# Personal website

### Setup

1. Install ruby dependencies
```shell
sudo apt update
sudo apt install autoconf bison build-essential libssl-dev libyaml-dev libreadline6-dev zlib1g-dev libncurses5-dev libffi-dev libgdbm5 libgdbm-dev
```
2. Install rbenv
```shell
git clone https://github.com/rbenv/rbenv.git ~/.rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bashrc
source ~/.bashrc
```
3. Install ruby build plugin to rbenv
```shell
git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
```

4. Install ruby
```shell
rbenv install <ruby_version>
rbenv global <ruby_version>
```

5. Install jekyll
```shell
gem install jekyll bundler
```

6. Run website
```shell
bundle exec jekyll serve
```

Details can be found in the jekyll docs.
