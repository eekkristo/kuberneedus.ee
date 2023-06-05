Setting up locally
___
1. Install https://jekyllrb.com/docs/installation/
. Run in root folder of the repository 
```console
bundle
```
 In order to add a post paste it into the ```_posts``` folder. On top of the folder add the following:
```console
---
title: <Title of the post>
author: <author>
date: 2023-06-05 12:55:00 +0800
categories: [Kubernetes]
tags: [kubernetes] # Use lowercase letters only
pin: true
---
```
Post has to start with YYYY-MM-DD-*
 
```NB! In order to add yourself as an author, add the following to _data->authors.yml ```
```console
More info › https://github.com/jekyll/jekyll-seo-tag/blob/master/docs/advanced-usage.md#setting-author-url
-------------------------------------
 {author_id}:
   name: {full name}
-------------------------------------
```
3. Run the following in project root: 
```console
$ bundle exec jekyll s
```
4. NB! Currently ```default.html``` is overwritten with coming soon page. In order to retrieve the blog version rename ```default.html```to ```default_.html```and ```default_blog.html```to ```default.html```
