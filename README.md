# Ribbit

An interactive Shell script that generates a personal Jekyll website with links to your various publications by using Bibtex references.

![](ribbit.png)

## Installation

`ribbit` depends on [`pandoc-citeproc`](https://github.com/jgm/pandoc-citeproc) to generate the YAML frontmatter from Bibtex files. This plugin comes preinstalled with [pandoc](https://pandoc.org/).

Make sure you have [Jekyll](https://jekyllrb.com/) installed on your machine. Please refer to the installation page for more information: https://jekyllrb.com/docs/installation/.

## Usage

You can use the interactive `ribbit` Shell script to generate your website.

```
$ ./ribbit 
Title of website: Ribbit
Your email address: contact@example.com
Link to profile pic: https://i.imgur.com/XjjuOdg.png
Your description: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
Your Twitter handle: Twitter
Your GitHub handle: GitHub
Name of bibtex file: text.bib
Navigate to http://localhost:4000/ to see your website.
```

Once you are done, simply navigate to http://localhost:4000/ to view your website.