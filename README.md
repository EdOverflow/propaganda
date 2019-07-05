<div align="center">
<img align="center" src="https://user-images.githubusercontent.com/18099289/60742609-54d56180-9f6e-11e9-9c5a-3e0009b7c707.png" height="200">
</div>
<h1 align="center">Propaganda</h1>

An interactive Shell script that generates a personal Jekyll website with links to your various publications by using Bibtex references.

```
                                Bibtex → YAML → _config.yml → Jekyll
```

![](propaganda.png)

## Installation

`propaganda` depends on [`pandoc-citeproc`](https://github.com/jgm/pandoc-citeproc) to generate the YAML frontmatter from Bibtex files. This plugin comes preinstalled with [pandoc](https://pandoc.org/).

Make sure you have [Jekyll](https://jekyllrb.com/) installed on your machine. Please refer to the installation page for more information: https://jekyllrb.com/docs/installation/.

## Usage

You can use the interactive `propaganda` Shell script to generate your website.

```
$ ./propaganda 
Title of website: propaganda
Your email address: contact@example.com
Link to profile pic: https://i.imgur.com/XjjuOdg.png
Your description: Lorem ipsum dolor ...
Your Twitter handle: Twitter
Your GitHub handle: GitHub
Name of bibtex file: text.bib
Navigate to http://localhost:4000/ to see your website.
```

Once you are done, simply navigate to http://localhost:4000/ to view your website.

<a href="https://www.buymeacoffee.com/edoverflow" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
