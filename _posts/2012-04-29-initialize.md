---
layout: post
title: "initialize"
description: ""
category: 
tags: [geek, tech,]
---
{% include JB/setup %}

It took about a week (outside of working hours) to set up and customise this blog.  I came across a few new technologies and websites along the way.  With the objective of setting up a blog using jekyll to be hosted on github, here's what I did.

1. Download and install Ruby Version Manager (RVM) using CURL (in order to install latest version of Ruby that's not available from apt-get)
 
        [kwan@host]$ curl -L get.rvm.io | bash -s stable

2. Install latest version of Ruby (and the gem) [ref](http://docs.rubygems.org/read/chapter/3#page83):

        rvm install 1.9.3

3. Set default version of Ruby:

        rvm --default use 1.9.3

4. Install jekyll

        gem install jekyll

5. [Install jekyll-bootstrap] (http://jekyllbootstrap.com/index.html#start-now)

6. Download and install the Mark Reid theme and customised it

7. Use [colorschemedesigner.com] (http://colorschemedesigner.com/) to help pick a colour scheme; also had a look at [http://www.colr.org/](http://www.colr.org/) and [http://www.colorschemer.com/online.html](http://www.colorschemer.com/online.html)

8. For ALL the photos to be uploaded, CSS classes have been added - these came from [zurb.com](http://www.zurb.com/playground/css3-polaroids)

9. [dummyimage.com](http://dummyimage.com/) is used to generate custom-sized images for testing.

10. [dabblet.com](http://dabblet.com/) is used as a sandbox type instant-response CSS/HTML editor.

11. Did a git push back to github but it's been a few hours and I still don't see the index page ... shall have to wait and see ...
	
