+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
url = '/{{ replace .File.ContentBaseName "-" " " | title }}/'
date = {{ time.Now.Format "2006-01-02" }}
draft = false
banner = "img/banners/website-launch.webp"
tags = ["", ""]
categories = [""]
+++
## {{ replace .File.ContentBaseName "-" " " | title }} ##