---
layout: post
title:  "Jekyll in Windows: I took a week to install Jekyll"
date:   2017-12-21
author: Eric Seo
categories: Jekyll
tags:	Jekyll
cover:  "/assets/instacode.png"
---

Ok, I took a week to install Jekyll.

Jekyll is a good static site generator(Am I right?). It is easy to install with good other blogs. 

However, I spend a week. Let me share my failure experience.

I tried to use Jekyll-theme-slate. This Theme is uncommon which does not make a post in _post/. 
I think this is the theme for really simple site which contains only informations about certain project. 
Therefore, if you want to run a blog, then please do not use theme-slate.

You may see some recommendations of jekyll themes. Try them and save your time :)

Finally, for window users, I summarize how I install jekyll with Contrarium themes in below.

1. Install git or github, use git-bash as your default git editor.
2. Install ruby 2.4.x with ruby installer. Dev kit will pop-up after ruby install. Don't kill it. 
3. Install Dev kit called MSYS2 with MINGW64 or MINGW32. (if you skip this, Make error will appears during jekyll installation.)
4. Download contrarium themes and use it as skeleton. 
5. Open your git editor, type 'gem install bundler' then type 'bundler install'
6. Connect your git repository to remote repository.
7. Check in local using 'bundle exec jekyll serve'

Maybe I miss some steps. If you have problems with these steps, please send me a email and let's solve it TOGETHER!

 
