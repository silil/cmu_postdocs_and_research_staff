# CMU Postdocs and Research Staff

The content of this site has been made with [Jupyter book](https://jupyterbook.org/stable) 

## Requirements 

- Python >= 3.10.x
- A virtual environment with the packages in the `requirements.txt` installed (`pip install -r requirements.txt`)

## How to add new content 

You'll need to have a local copy of this repository to add or modify content. 

1. Update or generate a markdown file
2. Commit and push the changes made ONLY on markdown files 

⚠️ DO NOT commit anything generated from `jupyter-book`: Anything in the `_build` folder or any of the `html` files generated in that folder. Those files will be managed directly by `jupyter-book`.

Once you have pushed the changes on the `main` branch Jupyter Book will triger the action that will publish the updated site. 

### Adding another section 

If you are adding another section to the site you need to modify the `myst.yml` file on the section `toc` and add the name of the markdown file which **must** be living on the `docs` folder.

## Experiencies template 

In order to have standarized experiencies on the visa section, try to follow this suggested template: 

```
[Title] 
[When it happened]

[Details of the event/experience]

[Time it took]

[Tips (if any) and useful links]

[Name (if allowed/wanted)] - [Department]
[Who to contact in OIE]
```

Here is an example: 

<div style="background-color: #f0f0f0; padding: 10px;">
<h2>From TD -> TN -> TD again, process for dependant visa</h2>

<h3>November 2025</H3>

My husband originally had a TD visa attached to my CMU-TN visa. Eventually, he found a job and got his own TN visa. In october 2025, his employer didn't renew his contract and legally he had **60 calendar days** to either get a new job that could sponsor another TN visa or update his legal status to his original TD visa. 

To udpate your dependant visa to the original TD you don't need any paperwork from CMU. You just need to file a File Form I-539 and you can do it online. 

...

*Anonymous* - **Machine Learning Department**

Who to contact in OIE: **Linda Gentile**
</div>