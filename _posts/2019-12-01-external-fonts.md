---
layout: post
author: draw.io
slug: external-fonts
date: 2019-12-01 09:21:00
title: Using external or custom fonts in draw.io
tags: [features, fonts]
categories: [features, text]
---

If you don't want to use the fonts that are available by default in draw.io, you can use your own custom fonts or external fonts, such as Google's fonts or web fonts stored on your own server. This is useful when you need to match the style guide of a publication, your company's corporate image, or to add interest and emphasis in an infographic.

It's easy to specify a different system font, use a Google font, or even use your own web font by providing its URL.

## How to use a different system font

System fonts are those which are stored on your computer or system. To use a different system font, you'll need to know the font's name.

<img src="/assets/img/blog/use-custom-font-text-tab-format-panel.png" style="max-width:100%;height:auto;" alt="Open the custom font selector via the Text tab in the format panel">

1. Click on the shape or text that you want to change.
2. In the _Text_ tab of the format panel on the right, click the drop down arrow next to the font name, and click _Custom_ (at the bottom of the list).
3. In the font selection dialog, type the name of the new font, then click Apply. This example uses the ``Charter`` system font.
   <br /><img src="/assets/img/blog/use-system-font-example.png" style="width=100%;max-width:300px;height:auto;" alt="Enter the name of a new system font">

You'll see your changes applied to the shape or text.

## How to use a Google font

To use a [Google font](https://fonts.google.com), all you need to know is Google's font name. This example uses the ``Satisfy`` Google font.

1. Click on the shape or text that you want to change.
2. Select the _Text_ tab in the format panel if it is not active, then click on the drop down arrow next to the font name, and on _Custom_.
3. Click on the _Google Fonts_ radio button, type the name of the Google font in the _Font Name_ text field, then click _Apply_.
   <br /><img src="/assets/img/blog/use-google-font-example.png" style="width=100%;max-width:300px;height:auto;" alt="Enter the name of a new Google font">

### How to use Google font weights

To use a specific weights for a Google font, you can specify the weights in the URL of the font in the Web Fonts section. For example, to use the ``Roboto Condensed`` Google font with a weight of 200 (normal) and 900 (bold), you would enter ``Roboto Condensed`` for Font Name and ``https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@200;900`` for Font URL in the Web Fonts section.

## How to use a web font stored externally

You can also use your own web fonts stored somewhere on the web. You need to link to the font file with the file type extension ``.woff``. The example below uses the italics version of the open source web font called SourceSans Pro.

1. Host your raw web font file somewhere on the web that can be directly accessed via the browser.
2. Click on the shape or text you want to change.
3. Select the _Text_ tab in the format panel, click on the drop down arrow next to the font name, then click on _Custom_.
   <br /><img src="/assets/img/blog/use-web-font-example.png" style="width=100%;max-width:300px;height:auto;" alt="Enter the name of a new system font">
4. Click on the _Web Fonts_ radio button, enter a name in the _Font Name_ field, then enter the URL where your ``.woff`` font file is stored. Then click _Apply_.

<img src="/assets/img/blog/use-custom-font-examples.png" style="max-width:100%;height:auto;" alt="Shapes with labels using custom fonts">
