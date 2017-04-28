# README.md

This file documents how to edit the website [mathcoop.github.io](http://mathcoop.github.io).

This website is hosted on [Github Pages](https://pages.github.com), which automatically compiles websites built with [Jekyll](https://jekyllrb.com), a utility that distinctly separates *styling* (written in this website with various HTML layouts, Liquid templates, and LESS/CSS files) and *content*. Most content for this website can be found in [Markdown](https://daringfireball.net/projects/markdown/).

If you are not familiar with any of what is written above, do not worry! Let us assume that your primary role is to edit *content*, not *styling*. In this case, we **highly** recommend reading the guide on [Markdown basics](https://daringfireball.net/projects/markdown/basics), which covers various elements such as: emphasis (bold, italics); content organization (headers, paragraphs, lists); HTML elements (links, images); etc.

---

## Getting started


1. Download [Github Desktop](https://desktop.github.com) (feel free to skip if you are otherwise familiar with `git`).
2. Log in with account `mathcoop`. If you need the password, contact `stevensoojinkim@gmail.com`.
3. Clone repository `mathcoop.github.io` onto your local machine.
4. Edit content as you please (see next section). If you would like an editor that syntax-highlights Markdown's `.md` files, I recommend [Atom](https://atom.io).
5. As you make changes, you can **commit** (record local changes), **pull** (grab updates from remote GitHub repository), and **push** (transfer your local changes to the remote repository). If you are using GitHub Desktop, this is combined in the single button "Commit and Sync (master)". Updates may take a few minutes.

---

## Editing content

There are numerous files and folders in this repository, but if you are solely editing content, then it suffices to look at the following:

* `/_posts/` : Whenever you wish to create a new page (i.e., display a new CoOp presentation), create a new Markdown file in this folder, with the naming syntax `YYYY-MM-DD-title-separated-with-hyphens.md`. There are various fields you should include in the header of each document; the easiest way to see how these pages work is to look at existing examples. The field `presurl` is the destination of the link in the gallery-type homepage of `mathcoop.github.io`. Note that the file `2015-01-01-other.md` is unique, and links to a webpage, not a pdf, because of its unique `presurl` field.
* `/images/` : This folder contains images that are shown in the gallery-type homepage of `mathcoop.github.io`, which are also referred to in the `image` field of each post.
* `/pres/` : This folder contains the PDF files of the presentations, which are referred to in the `presurl` field of each post.
* `/about.md` : This file contains content for [mathcoop.github.io/about/](http://mathcoop.github.io/about/).
* `/people.md` : This file contains content for [mathcoop.github.io/people/](http://mathcoop.github.io/people/).

---

## Changing the URL

If you have purchased a custom domain and would like to change the URL from `mathcoop.github.io` to your custom domain, then see [Github Help](https://help.github.com/articles/using-a-custom-domain-with-github-pages/).

---

## Details

If you delve deep into **styling** rather than content (e.g., playing around with LESS files, Liquid templates, etc.), you will need to re-compile via the `grunt` command in terminal.
