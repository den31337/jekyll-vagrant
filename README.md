# jekyll-vagrant
Development environment for Jekyll

Requirements: vagrant and virtualbox.

## Setting up
Run vagrant and SSH into VM:
```
vagrant up
vagrant ssh
```
Jekyll is installed! (more details in bootstrap.sh of this repository)

## Initializing and running website
Initialize new website under '/vagrant/mysite':
```
cd /vagrant
jekyll new mysite
```
Run Jekyll:
```
cd mysite
bundle exec jekyll serve --host=0.0.0.0 --force_polling
```
Access your website from host OS at `http://localhost:4000`
