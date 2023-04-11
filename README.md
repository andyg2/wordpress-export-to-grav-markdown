# wordpress-export-to-markdown

A script that converts a WordPress export XML file into Markdown files suitable for [Grav](https://getgrav.org/) static site generator.

Each post is saved as a separate Markdown file with appropriate frontmatter. Images are also downloaded and saved.

## Quick Start

You'll need:

- [Node.js](https://nodejs.org/) v12.14 or later
- Your [WordPress export file](https://wordpress.org/support/article/tools-export-screen/) (be sure to export "All content" if you want to save images and/or pages)

It is recommended that you drop your WordPress export file into the same directory that you run this script from so it's easy to find.

Clone and run (this makes repeated runs faster and allows you to tinker with the code). After cloning this repo, open your terminal to the package's directory and run:

```
npm install && node index.js
```

## Options (use default options)
