---
layout: post
title: "jekyll的前缀url"
description: ""
category: 
tags: []
---
{% include JB/setup %}
目的：把blog的内容放在daxiazihy.com/blog下面  

apache conf设定  

    Alias /blog /usr/share/blog  
    <Directory /usr/share/blog>  
      Options +FollowSymLinks  
      AllowOverride None  
      order allow,deny  
      allow from all  
    DirectoryIndex index.html  
    </Directory>  

jekyll设定`BASE_PATH = /blog`
启动时command需要改为`jekyll serve --safe`
