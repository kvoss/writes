---
title: "Site"
date: 2025-02-22T16:50:33-06:00
draft: false
toc: false
images:
tags:
  - untagged
---
## Starting a website

I use [4bes.nl tutorial](https://4bes.nl/2021/08/29/create-a-website-with-hugo-and-github-pages/) to generate a static website and publish it on github pages.

For CI/CI, I followed [Marie Cruz' article](http://www.testingwithmarie.com/posts/20241126-create-a-static-blog-with-hugo/)

## Lessons

The CICD config on Marie's page needs an adjustment as for the publishing folder. The tutorial publishes generated pages to `docs` instead of `public`.

Likely, the files generated using the tutorial are not needed. I will remove them in a future commit. This commit tests the update to contents after changing the content of a post.
Starting with deleting the `./docs/` content. It is generated.

The `./themes/` may be necessary, although we have a reference to it in git submodules.

