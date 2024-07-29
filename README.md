# Tangerine

Welcome to Tangerine! This is a Jekyll theme designed for personal blogs.

## Site address

- [GitHub](https://github.com/WCY-dt/tangerine)
- [Demo](https://tangerine.ch3nyang.top/)
- [My own blog](https://blog.ch3nyang.top/)

## Local development

You are free to use the theme of this blog for your blog.

It is recommended to use the Visual Studio Code editor and install the plugins [`Shopify Liquid`](https://marketplace.visualstudio.com/items?itemName=Shopify.theme-check-vscode), [`markdownlint`](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) and [`Live Server`](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for a better development experience.

Install Ruby and Jekyll before building, and then install dependencies:

```bash
bundle install
```

Start the local service:

```bash
jekyll serve
```

Then use [`Live Server`](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) to preview the real-time updates.

Most of the settings are in the [`_config.yml`](./_config.yml) file, which you can modify according to your needs.

Blog posts are stored in the [`_posts`](./_posts) folder, with the naming format of `YYYY-MM-DD-title.md`. The header of the blog post should contain the following information:

```yaml
layout: post
title: "Genshin Impact Game Guide"
date: 2000-01-01 00:00:00 +0800
categories: Games // There can be only one category
tags: Open World RPG Genshin Impact // There can be multiple tags, separated by spaces
comments: true // If set to true, the article will display the comments area; otherwise, it will not be displayed
mathjax: true // Omitted, defaults to false. If set to true, mathematical formula support will be enabled
mermaid: false // Omitted, defaults to false. If set to true, flowchart support will be enabled
copyrights: original // If set to original, the copyright notice will be displayed at the end of the article; otherwise, it will not be displayed
draft: true // Can be omitted, defaults to false. If set to true, the article will not be displayed on the homepage
```

You may also need to modify the workflow files, website icons and [`CNAME`](./CNAME) in the [`.github`](./.github) folder to suit your needs.

You can use the test articles in the [`_test`](./_test) folder for testing.

## Features

- Personalized theme
- Article classification
- Article tag
- Article series
- Code highlighting
- Code copying
- RSS subscription
- Responsive design
- SEO optimization
- Copyright statement
- Performance optimization
- Article search
- Related article recommendation
- Comment system
- Article directory
- Article sharing
- Theme switching
- Formula support
- Flowchart support

## Copyright statement

All of the code in this blog uses the [MIT](https://opensource.org/licenses/MIT) license agreement.
