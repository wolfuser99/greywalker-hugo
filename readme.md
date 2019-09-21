# Hugo Site

Deploy state: [![Netlify Status](https://api.netlify.com/api/v1/badges/f40d829e-a0f5-401e-a6be-8544ba18acd4/deploy-status)](https://app.netlify.com/sites/xenodochial-archimedes-044171/deploys) https://greywalker.tk

[https://gohugo.io](https://gohugo.io/)

## To Replicate this blog

1. Install the Hugo CLI from chocolatey(windows), apt(ubuntu) or their [official page](https://gohugo.io/).
2. `hugo new site blog`
3. `cd blog && git init`
4. `git submodule add https://github.com/halogenica/beautifulhugo.git themes/beautifulhugo`
5. Copy and adapt the configuration from *themes\beautifulhugo\exampleSite\config.toml*
5. `hugo new post/2019/10-09-post-title.md` or `hugo new post/$(date +%Y)/$(date +%d-%M)-post-title.md` #unix
6. `hugo server` or `hugo server -D`  # to get drafts


## To Dev

1. Install the Hugo CLI from chocolatey(windows), apt(ubuntu) or their [official page](https://gohugo.io/).
2. `git clone git@github.com:wolfuser99/greywalker-hugo.git && cd greywalker-hugo`
3. `git submodule update --init`
4. `hugo server` or `hugo server -D`  # to get drafts


## Bugs

- if change the folder of post to posts the post's meta info and bigimg stop working correctly.

