---
layout: post
title:  "Install Node & NPM"
date:   2015-07-29 16:42:08
---



Update the system

```sudo apt-get update```

```sudo apt-get install git-core curl build-essential openssl libssl-dev```


Downloadg the node files

```git clone https://github.com/joyent/node.git```

``` cd node ```
 
Install the node with specific version

```
git tag

git checkout 

configure

make

sudo make install

```

Check the version of the installed node to verify

``` node -v```
