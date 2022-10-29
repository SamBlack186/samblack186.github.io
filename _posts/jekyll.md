---
title: Installing Jekyll
date: 10-29-2002 16:30:00
categories: [homelab]
tag: [jekyll, documentation]
---

## Install Ruby
```bash
sudo apt update && sudo apt upgrade -y
```
```bash
sudo apt-get install ruby-full build-essential zlib1g-dev git
```

## Install Bundler
```bash
gem install bundler
```

## Clone Repo
```bash
git clone https://github.com/SamBlack186/samblack186.github.io
```

## Host Jekyll
```bash
bundle exec jekyll s --host=0.0.0.0
```