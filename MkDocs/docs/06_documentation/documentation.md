Documentation
=============

Pandoc
-------

For better collaboration in writing, correcting and following up on any
changes we decided to write the documentation for this project on
cloud-hosted word-documents. But because our final documentation has to
be a markdown file we needed something to convert from word to markdown.
For this task we use [Pandoc](https://github.com/boisgera/pandoc).

Installing Pandoc:
```command
pip install pandoc
```
Converting word document to markdown:
```command
pandoc -f docx -t markdown your_file.docx -o your_file.md
```

MkDocs
------

[MkDocs](https://www.mkdocs.org/) is a static site generator for
building project documentation on a markdown basis.

```
pip install mkdocs
```

For a more appealing design, we chose [Material for
MkDocs](https://squidfunk.github.io/mkdocs-material/).

````
pip install mkdocs-material
````

Because we also wanted to show videos in our documentation we installed
the [Plugin MkDocs
Video](https://github.com/soulless-viewer/mkdocs-video).
```
pip install mkdocs-video
```

For converting our documentation into pdf we used the VSCode Plugin [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).


**Commands**:

| Feature:                              | Command:                      |
|---------------------------------------|-------------------------------|
| Create a new project.                 |     ``mkdocs new [dir-name]`` |
| Start the live-reloading docs server. |     ``mkdocs serve``          |
| Build the documentation site.         |     ``mkdocs build``          |
| Print help message and exit.          |     ``mkdocs -h ``            |
