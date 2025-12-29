# CMU Postdocs and Research Staff

The content of this site has been made with [Jupyter book](https://jupyterbook.org/stable) 

## Requirements 

- Python >= 3.10.x
- A virtual environment with the packages in the `requirements.txt` installed (`pip install -r requirements.txt`)

## How to add new content 

You'll need to have a local copy of this repository to add or modify content. 

1. Update or generate a markdown file
2. Commit the changes made ONLY on markdown files 

⚠️ DO NOT commit anything generated from `jupyter-book`: Anything in the `_build` folder or any of the `html` files generated in that folder. Those files will be managed directly by `jupyter-book` and the `ghp-import` package.

## How to build it

To generate the `html` pages from the markdowns, you'll need to build the `jupyter book`. You can do that with the following commands (at the root of the project):


$ jupyter-book clean cookbook/
$ jupyter-book build cookbook/
️ Please read the warning messages and try to solve them before publishing the content. Most of the times are missing references to figures/images/sections that affect the flow of the content.

## How to udpdate the github page

To publish your `html`s to the GitHub Page you'll need to tell GitHub that you have new static content. To do that, you use the `ghp-import` tool that triggers the flow to publish your content on your GitHub site.


$ ghp-import -n -p -f cookbook/_build/html


Verify that the page has been updated at dssg.github.io/cmu_postdoc_and_research_staff
