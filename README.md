"# talesfromtim.io" 

This blog was built using Jekyll. Soemwhat helpful instructions at [Jekyll docs](https://jekyllrb.com/docs/) and [Github pages docs](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

Note for future Tim, this may be painful to reinstall. Here's vaguely what I tried -

```
sudo apt update
sudo apt install -y build-essential libssl-dev libreadline-dev zlib1g-dev \
                    libsqlite3-dev libffi-dev libgdbm-dev libgmp-dev \
                    libncurses5-dev libyaml-dev libxml2-dev libxslt1-dev \
                    autoconf bison

sudo apt install -y gcc

#Install RVM using something like https://github.com/rvm/ubuntu_rvm

#then install ruby via rvm (instead of directly via apt)
rvm reinstall 3.1.2

sudo gem uninstall bundler --version '<2' && gem install bundler

#These commands probably didn't help but I tried them anyway
gem update jekyll
gem pristine --all
gem install liquid -v 4.0.4
sudo gem install cocoapods --pre -n /usr/local/bin

gem install bundler --user-install
bundle install
```

Once everything is installed and works*, test using

```
bundle exec jekyll serve
```
