---
# Replace the text on this page with content
# for your your own project's landing page.
title: Raymond Lee's Chinese Classic Translations
style: home
opener-image: banner-image.jpg
opener-image-alt-text: "An illustration of an enormous book. It is open, and its pages are each filled with an image of a starry sky. Beside the book, a man stands and looks at the pages. The book is bigger than he is."
opener-image-position: "0 60%"
---

# Modern English Translations of Chinese Classicss

<div class="feature-boxes">

{% include feature-box
   text="Personal translation of the [Dao de Jing](daodejing/0-3-contents.html)."
   image="logo.svg"
   link="daodejing/0-3-contents.html"
%}

{% include feature-box
   text="Learn from [a book of examples](samples/index.html), with a partial [translation](samples/fr/)."
   image="cover.jpg"
   image-position="0 35%"
   link="samples/index.html"
%}

{% if site.output == "web" and output-docs == true %}

{% include feature-box
   text="The template's [documentation](docs/) explains how its features work."
   image="banner-image.jpg"
   image-position="0 65%"
   link="docs/"
%}

{% endif %}

</div>

You'll find [the open-source repository on GitHub](https://github.com/electricbookworks/electric-book).

<div class="color-panel background-000 text-fff links-ccc" markdown="1">

## Skills required

To make books this way, you need some web-development know-how. You'll edit content in markdown with Liquid template tags; edit data in YAML files; commit your changes with Git; enter commands at the command line; and build and serve a static website. Design is done in Sass. Many features are written in Javascript.

If those concepts are not familiar to you, you'll need a web developer on your team to get you going, and to provide you with technical support when you get stuck.

You can also hire [Electric Book Works](https://electricbookworks.com) to handle setup or book production for you.

</div>

## Sample content

To see how these examples look in other formats, [download PDF and epub versions of the sample book](https://www.dropbox.com/scl/fo/uskmdm77do6s16r4mbwy4/AIrPyibgt3AFLumX-FFzYjk?rlkey=vuyn7dysx5w1d9texgemsioix&st=3nouz3mx&dl=0).

{% include visual-toc
   book="samples"
   files="
   * 00-05-contents-page
   * 01-01-plain-text-1
   * 01-10-questions
   * 02-01-plain-images
   * 02-02-figures
   * 03-02-maths
   * 04-02-video
   * 10-02-dynamic-index
" %}


<div class="color-panel text-000 links-ccc" markdown="1">

## Features

### Web, mobile, and print

You can instantly output print PDF, screen PDF, epub, website and app versions of your books from a single content source.

### Series and collections

Create a series or collection of books in one website or app. They can share common designs, features and [metadata]({{ site.baseurl }}/docs/setup/metadata.html).

### Fast and mobile-friendly sites

The template generates a static website, which is secure, easy to host, and lightning fast. It's also designed to be mobile-friendly throughout.

### Windows, Mac, Linux

You can use the template on Windows, Mac and Linux computers. We recommend working in your browser with [Gitpod](https://gitpod.io), in which case you don't need to install anything on your computer.

### Documentation

The docs you need are embedded in your project, including guidance on [how to edit in markdown]({{ site.baseurl }}/docs/editing/markdown.html).

### Online editing

Team members can contribute online by either editing files on GitHub directly, or by using Gitpod. Our built-in Gitpod support means you can instantly start editing and generating a website, ebooks and PDFs. [Launch a testing environment here right now](https://gitpod.io/#https://github.com/electricbookworks/electric-book){:target="_blank"}.

### Export to Word

Sometimes you need your book in MS Word format. For instance, an author might be working on a new edition. You can easily, instantly [export books to MS Word]({{ site.baseurl }}/docs/output/word-output.html).


## Design and layout

### Built-in book features

Select from dozens of [built-in tags for common book features]({{ site.baseurl }}/docs/editing/classes.html), such as boxes, epigraphs, sidenotes and bibliographies.

### Easy design settings

We deliberately made this template look plain – it's ready for your design flair. Quickly change the design with [dozens of simple settings]({{ site.baseurl }}/docs/layout/design.html), from fonts and sizes to the position of page numbers and the width of your sidebar. Then add your own CSS stylesheets. [See the Electric Book Works portfolio for examples of what's possible](https://electricbookworks.com/work/).

### Mathematics

[Include complex maths]({{ site.baseurl }}/docs/editing/maths.html) using LaTex notation.

### Refined page typography

For high-quality print publishing, [control letter-spacing]({{ site.baseurl }}/docs/editing/classes.html#formatting) in individual paragraphs for page refinement. There are many other page-refinement tags available for advanced users.

### Optimised images

[Automatically convert your master images]({{ site.baseurl }}/docs/images/image-conversions.html) to optimized sizes and color profiles. For instance, CMYK for print, and RGB at different sizes for large vs mobile screens.

### Books indexes with automatic page numbers

Create back-of-the-book indexes where page numbering is automated, and the index works in website and ebook editions, too. [Read more at Electric Book Works](https://electricbookworks.com/thinking/dynamic-digital-book-indexes/).