---
layout: post
title: You don't need Ruby to deploy Jekyll on Github Pages
subtitle: Deploy Jekyll on Github Pages is easier than ever
thumbnail-img: /assets/img/blog-screenshot.png
tags: [tutorial,blog,github]
comments: true
---

If you go the [Jekyll Official Docs](https://jekyllrb.com/docs/) you will be directed to install ruby along with it's dependencies to start build your Jekyll page. I mean it's not wrong, but what if I tell you that you don't really need to follow those step. Those step is only fits for anyone who interested in building Jekyll from scratch using Ruby since Ruby is the programming languange of which the Jekyll is build. 

Offcourse there's pros and cons of building the Jekyll from scratch. One of the pros is flexibility since you can add anything to you Jekyll that fits you. But the const is well you waste your time and waste your storage space for the development since Ruby and its dependecies can takes up to hundreds of mb of your storage. Instead of build you Jekyll from scratch why don't you just fork it from someone's Jekyll Themes that has all the function you need? 

There's thousands of available Jekyll Themes that you can use and modified to fits your style instead of wasting time building it from zero. From blog themes to Portfolio themes, there's so many Jekyll Themes fits your need. You can modified it, and add content to it easily without having to deal with Ruby programming languange. Here are the steps:

1. Search for the Jekyll themes you want to use, i recomended [Github Jekyll Themes](https://github.com/topics/jekyll-theme) since it's perfectly supported by Github Pages.
2. Let's use [Beautiful Jekyll](https://github.com/daattali/beautiful-jekyll) themes by clicking it to enter the repository page. And click the *fork* button in top right corner of the repository page. ![choose-theme](/assets/img/choose-theme-screenshot.png)
3. Click *Settings* and chhange the repository name to {your-username}.github.io. Github pages only allow your username to be use as domain name for the free , if you want custom domain name you need to buy one, and it hass different process, for now let's stick to your free github pages. Don't forget to save the changes. ![change-repo-name](/assets/img/change-repo-name.png)
4. Head to {your-username}.github.io that you've build, your Github pages will be deployed in couple of minutes with the themes that you've forked. Congratulations! ![blog-screenshot](/assets/img/blog-screenshot.png)
5. You can change the themes configuration by heading to \_config.yml and change some of it's lines like your blog title, email, or author name. ![edit-config](/assets/img/edit-config.png)
6. Post your content by creating and uploading your MD file to \_post. You can copy the existing example post and change the content. You can read the readme that included the themes for further experiment. You can learn how to write MD file in 5 minutes [here](https://www.markdownguide.org/basic-syntax/)
7. Enjoy your website!
