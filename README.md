# vagnrat-graphite


## Setup Homebrew
Use [Homebrew](http://brew.sh/).

```
ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"
```

## Setup Vagrant

Install VirtualBox and Vagrant using [Brew Cask](https://github.com/phinze/homebrew-cask).

```
brew tap phinze/homebrew-cask
brew install brew-cask
brew cask install virtualbox
brew cask install vagrant
```

Use the lucid32 vagrant box: [http://docs-v1.vagrantup.com/v1/docs/boxes.html](http://docs-v1.vagrantup.com/v1/docs/boxes.html)

```
vagrant box add lucid32 http://files.vagrantup.com/lucid32.box
```


# Setup Berkshelf

Install Chef Cookbook using [Berkshelf](http://berkshelf.com/).

```
gem install berkshelf
berks install
```


## Run it!

```
vagrant up
vagrant ssh
```


