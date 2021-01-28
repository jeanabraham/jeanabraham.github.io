---
layout: post
title: Minishift on Mac OS
---

Here’s a quick list of steps you can run on your Mac to get up and running with Minishift:
```
brew update
brew install --HEAD xhyve
brew install docker-machine-driver-xhyve
sudo chown root:wheel $(brew --prefix)/opt/docker-machine-driver-xhyve/bin/docker-machine-driver-xhyve
sudo chmod u+s $(brew --prefix)/opt/docker-machine-driver-xhyve/bin/docker-machine-driver-xhyve
brew cask install minishift
minishift start
```
Voila!

For other platforms or more elaborate details, visit [minishift docs](https://docs.okd.io/3.11/minishift/index.html).