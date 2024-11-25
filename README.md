# Tangerine

[简体中文](./README_zh-CN.md) | English

![Hero Image](https://heroimg.glitch.me/hero?title=Tangerine&subTitle=A%20Jekyll%20theme%20designed%20for%20personal%20blogs&style=layered-peaks&subFontSize=32)

Welcome to Tangerine! This is a Jekyll theme designed for personal blogs.

## Site address

- [GitHub](https://github.com/WCY-dt/tangerine)
- [Preview](https://tangerine.ch3nyang.top/)
- [Demo](https://blog.ch3nyang.top/)

## Local Development

You are free to use the theme of this blog for your blog.

It is recommended to use the Visual Studio Code editor and install the plugins [`Shopify Liquid`](https://marketplace.visualstudio.com/items?itemName=Shopify.theme-check-vscode), [`markdownlint`](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) and [`Live Server`](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for a better development experience.

Before building, install Ruby and Jekyll, and then install the dependencies:

```bash
bundle install
```

Start the local service:

```bash
jekyll serve
```

Then use [`Live Server`](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) directly to preview the live updates.

Most of the settings are in the [`_config.yml`](./_config.yml) file, you can modify it according to your needs.

Blog posts are stored in the [`_posts`](./_posts) folder, and the naming format is `YYYY-MM-DD-title.md`. The file header of a blog post should contain the following information:

```yaml
layout: post
title: "Genshin Impact Gameplay Guide"
date: 2000-01-01 00:00:00 +0800
categories: Game // There can be only one category
tags: RPG Genshin // There can be multiple tags, separated by spaces
comments: true // If set to true, the article will display the comments area; otherwise, it will not be displayed
mathjax: true // Omittable, default is false. If set to true, mathematical formula support will be enabled
mermaid: false // Omittable, default is false. If set to true, flowchart support will be enabled
copyrights: Original // If set to Original, the copyright statement will be displayed at the end; otherwise, it will not be displayed
draft: true // Omittable, default is false. If set to true, the post will not be displayed on the homepage
```

You may also need to modify the workflow files, website icon [`favicon.svg`](./favicon.svg) and [`CNAME`](./CNAME) in the [`.github`](./.github) folder to suit your needs.

The images in the post are stored in the [`assets/post/images`](./assets/post/images) folder. If you need to reference the image, please use a relative path, for example:

```markdown
![Image description](/assets/post/images/image file name.webp)
```

The [`assets/post`](./assets/post) folder provides a script that can help convert images to webp format. If you need to use it, please install the [webp](https://developers.google.com/speed/webp) tool first.

You can use the test article in the [`_test`](./_test) folder for testing.

## Development route

- [x] Personalized theme
- [x] Article classification
- [x] Article tag
- [x] Article series
- [x] Code highlighting
- [x] Code copying
- [x] RSS subscription
- [x] Responsive design
- [x] SEO optimization
- [x] Copyright statement
- [x] Performance optimization
- [x] Article search
- [x] Related article recommendation
- [x] Comment system
- [x] Article directory
- [x] Article sharing
- [x] Theme switching
- [x] Formula support
- [x] Flowchart support
- [x] Accessibility
- [ ] More features...

## Copyright statement

All of the code in this blog uses the [MIT](https://opensource.org/licenses/MIT) license agreement.
