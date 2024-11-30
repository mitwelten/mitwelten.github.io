# Mitwelten Website
Hugo source code of the static part, to be hosted on www.mitwelten.org.

Hosting is not yet automated, you'll have to preview on your Mac.

Publishing requires copying files to [mitwelten.github.io](https://github.com/mitwelten/mitwelten.github.io).

## Install Hugo

On your Mac / PC, open a Terminal and type

This page is built with version v0.136.4. Older versions might not work.

If you want to install a specific version, visit the following link: [gohugo.io/installation](https://gohugo.io/installation/)

```
$ brew install hugo
```

### Check the Installation
```
$ hugo version
```
If you see a version number, you're good to go.


## Get this repo
To clone the repo with git, type

```
$ cd ~/Desktop # (or wherever you like)
$ git clone https://github.com/mitwelten/mitwelten.github.io
$ cd mitwelten.github.io
$ npm install autoprefixer
```

## Run a local server
To run a local Web server, type

```
$ cd ~/Desktop/mitwelten.github.io
$ hugo server -D
(visit http://localhost:1313/)
```

## Set up to publish
To set up publishing to www.mitwelten.org, type

```
$ cd ~/Desktop # (or wherever you keep mitwelten.github.io)
```

## Add new content

To publish to www.mitwelten.org (assuming you're [set up to publish](#set-up-to-publish)), type

Before you add new content, don't forget to pull the latest changes from the repository.

```
$ git pull
```

Open the content folder and add new content in markdown format. The content is structured in two languages (de and en).

If you add new pages, you need to add them to the menu. The menu is defined in the config folder.

### Publish new content

Open the terminal and navigate to your project folder.

```
$ cd ~/Desktop/mitwelten.github.io (or wherever you keep mitwelten.github.io)
$ hugo
$ git status # check changed files
$ git commit --all
$ git push
(visit https://www.mitwelten.org/)
```


## Check the file structure
```
$ cd ~/Desktop/mitwelten.github.io
$ brew install tree
$ tree

.
├── assets
│   ├── icons
│   │   └── logo.svg
│   └── scss
│       ├── _styles_project.scss
│       └── _variables_project.scss
├── config
│   └── _default
│       ├── hugo.yaml
│       ├── menus.de.yml
│       └── menus.en.yml
├── content
│   ├── de
│   │   ├── approach
│   │   ├── featured-background.png
│   │   ├── fieldstudies
│   │   ├── _index.md
│   │   ├── interventions
│   │   └── iot
│   └── en
│       ├── approach
│       ├── featured-background.png
│       ├── fieldstudies
│       ├── _index.md
│       ├── interventions
│       └── iot
│  
├── docs
├── layouts
│   ├── 404.html
│   ├── _default
│   │   └── _markup
│   ├── partials
│   │   ├── footer.html
│   │   └── navbar.html
│   └── shortcodes
│       ├── blocks
│       ├── swisstopo.md
│       └── test.html
├── LICENSE
├── README.md
└── static
    ├── docs
    │   ├── MW_IOT_TOOLKIT.pdf
    │   └── MW_Software_Environment.pdf
    ├── favicons
    └── images
        ├── applications
        ├── fieldstudies
        ├── interventions
        ├── iot
        └── logo

```

### Relevant folders

- config: general hugo configuration with standalone files for menus entries for each language
- static: static files like images, pdfs, etc.
- content: markdown files for the content of the website for each language
- layouts: html templates for the website (partials: only includes overwritten templates)

# Docs
The following links provide technical background.

## Installing & Usage
* https://gohugo.io/getting-started/installing/
* https://gohugo.io/getting-started/usage/

## Templates (based on HTML)
* https://gohugo.io/templates/base/
* https://gohugo.io/templates/homepage/

## Content Management (based on Markdown)
* https://gohugo.io/getting-started/quick-start/
* https://gohugo.io/content-management/archetypes/
* https://gohugo.io/content-management/shortcodes/

## Used Theme
* https://www.docsy.dev/
* https://github.com/google/docsy

Note: The theme uses bootstrap, therefore the following links might be helpful

* https://getbootstrap.com/docs/5.0/getting-started/introduction/
