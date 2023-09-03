+++
title = 'How I Made This Site'
date = 2023-09-03T13:49:31-06:00
draft = false
tags = ["hugo", "notes", "github"]
+++

## Installation
- I'm using Ubuntu 22.04
- install golang from the repo
- install ghostwriter from the repo
- install hugo - used the amd64 deb from the hugo website
- install GitHub desktop from github/shiftkey. Again grabbed the deb
- sign into GitHub desktop

## Starting
- Built the site in Dropbox/hugo/tedlinux
- cd tedlinux/themes
- grab the theme he used: `git clone https://github.com/cholinger93/inkfree.git`
- back to the tedlinux directory and `hugo new posts/my-first-post.md`
- my post has `+++` rather than `---` surrounding the front matter - that means it's toml rather than yaml like jekyll
- just put HI after the front matter
- rename hugo.toml in tedlinux ro hugo.toml.bak
- copy config.toml from themes/ink-free/exampleSite to tedlinux/
- I added some tags to my-first-post.md and they worked great, but only after I restarted the server
- He changed all the #9375fd in the themes/ink-free/static/css files to a color he like better
- I changed the copyright notice in config.toml to Created so now at the bottom of the pages it says 2023 Created. 
- Again in config.toml deleted all the social links except github and fixed that to terryinfcco

## Putting it on GitHub

