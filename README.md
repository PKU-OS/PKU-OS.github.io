## PKU Operating System Course Website
This repo contains the source code for the main page of PKU Operating System Course website. 

### How to use
In each new semester, you need to add one entry in the [index.md](./index.md) under the *Offerings* title and create a new website under the guidance in this [repo](https://github.com/PKU-OS/sp22).

You can use the [editor on GitHub](https://github.com/pmarsceill/test-jtd/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/pmarsceill/test-jtd/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

### Running Locally

This website is written using Jekyll Bootstrap with some modifications to
improve support for github pages.

Install `rvm`: https://rvm.io/

Install Ruby 2.2.0:

    rvm install 2.2.0

Clone this repo:

    git clone git@github.com:PKU-OS/PKU-OS.github.io.git

In the repo directory, run:

    gem install bundler
    bundle install

Finally, serve the project locally with:

    jekyll serve

This will start the local Jekyll server at http://localhost:4000.
