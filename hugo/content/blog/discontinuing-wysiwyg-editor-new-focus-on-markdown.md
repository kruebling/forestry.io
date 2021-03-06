---
title: Discontinuing WYSIWYG Editor - New Focus on Markdown
description: 'Considering the issues the WYSIWYG Editor causes and the merits Markdown
  provides we made the decision to discontinue our WYSIWYG / HTML Editor on 5/11/2018. '
date: 2018-04-10 08:57:29 +0000
authors:
- Scott Gallant
publishdate: 2018-04-13 03:00:00 +0000
expirydate: 2030-01-01 04:00:00 +0000
categories:
- CMS
headline: ''
textline: ''
images: []
tags: []
cta:
  headline: ''
  textline: ''
  calls_to_action: []
private: false
weight: ''
aliases: []
menu: []
draft: true

---
{{% tip %}}  
Forestry.io is currently using two editors. This article only affects those users that are using HTML (.html) files and not Markdown (.md) files to edit their content. Our Markdown Editor stays unaffected by this change.
{{% /tip %}}

The WYSIWYG / HTML Editor has proven to be less and less the state-of-the-art content editing experience it once set out to be. Considering the issues the WYSIWYG Editor causes and the merits Markdown provides we made the decision to discontinue our WYSIWYG / HTML Editor on 5/11/2018.

For those users that continue to use HTML over Markdown the Source View Editor continues to be available.

Since Markdown proves to be increasingly ubiquitous, we want to lay out clearly why we believe Markdown is the future and how you can make the move as well.

## Future-Proof Markdown

WYSIWYG Editors were created for a valid reason - HTML is hard to read and content editors shouldn't need to learn HTML to structure and write content. However, they are notoriously known for creating clunky, unreadable, hard to maintain code, affecting not only your ability to rank high on search engines but also the well-being of your developers.

Markdown maintains a simple readable text (e.g. \*\***word**\*\* **word**) that can be converted into consistent HTML. The styling will be applied separately and can be easily migrated to a new design without having to alter the content itself. Even if you don't want to learn the simple Markdown syntax your editors will be able to add content right away, the Markdown just spices things up.

With WYSIWYG Editors you often don't know whether content was formatted consistently without going into the code (e.g. H1 can often look similar to a larger sized font that was set to bold). Markdown takes care of this issue by forcing a consistent mark up through limiting options.

However, the big caveat is that editors won't be able to immediately see the styling of a heading, bold, italic or linked word it can make adoption slightly more difficult for non-tech users.![](/uploads/2018/04/Markdown-Editor.png)

To help with that content editors in Forestry.io use a Markdown editor that provides a simplified formatting giving content editors control over the styling of their article.

## Tools and Tips to Migrate Existing Site

We put together a few tips to make your migration easier.

### Automate Migration with Pandoc

If you need to convert files from one markup format into another, pandoc is your swiss-army knife. The learning curve is a little steep but if you have a lot of pages and you want to convert them automatically, this is a tool worth looking at.

[https://pandoc.org/](https://pandoc.org/ "https://pandoc.org/")

### Simple Paste and Translate

For those of you that just have a few pages to migrate, doing it manually might be more efficient and more accurate. A good tool to get a jump start on this is Dom Christie's Turndown project.

[https://domchristie.github.io/turndown/](https://domchristie.github.io/turndown/ "https://domchristie.github.io/turndown/")

### Import to Hugo and Migrate later

Maybe your old content doesn't necessarily need to be updated immediately. In that case just follow the tutorial below and get started with you new Hugo page and set up Markdown for any future updates.

[http://whipperstacker.com/2016/09/22/convert-an-existing-site-into-hugo/](http://whipperstacker.com/2016/09/22/convert-an-existing-site-into-hugo/ "http://whipperstacker.com/2016/09/22/convert-an-existing-site-into-hugo/")

{{% tip %}}  
A similar setup works for Jekyll as well. Consult the docs [https://jekyllrb.com/tutorials/convert-site-to-jekyll/](https://jekyllrb.com/tutorials/convert-site-to-jekyll/ "https://jekyllrb.com/tutorials/convert-site-to-jekyll/")  
{{% /tip %}}

At Forestry.io we want to provide you with the best content editing experience and we believe Markdown gives us the simplicity to start creating content for static sites right away and the flexibility to further improve your editor over time.