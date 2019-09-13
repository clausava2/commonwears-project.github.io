# How to contribute

## Prerequisites

* Minimal proficiency with [git](https://learnxinyminutes.com/docs/git/)
* Proficiency in [Markdown](https://learnxinyminutes.com/docs/markdown/)

## Import

1. Clone the repository with `git@github.com:Fluidware-Project/fluidware-project.github.io.git`

## Editing

The `pages` folder contains the website pages:

* `consortium.md` is the consortium page
* `prototypes.md` is the software and prototypes page
* `publications.md` is the page listing the publications. It is actually generated, so this one should not get touched.

### Adding a new paper

In order to add a new publication, navigate to the `_posts` folder.
Here, you'll find a file named `3019-09-10-sample-publication`.
Copy it, changing its name so that it starts with the publication date in format `YYYY-MM-DD`.
After the date, you can use a name of your like.
The naming format *is mandatory*, inventing your own custom format won't let the publication appear.

It's now time to edit the file. In the header, change paper title, authors, keywords, journal (or proceedings), and DOI.
Once done, paste the abstract.
If you want to write a different introduction, or you want to control what appears as excerpt in the publications main page, use `<!--more-->` to cut: what's before such comment will be displayed in the publications home page, the rest will be accessible if the publication is clicked on.

The example file should contain a decent guide inside.
Please look at it.