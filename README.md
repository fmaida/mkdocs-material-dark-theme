# mkdocs-material-dark-theme

External SCSS/CSS file that can change the appearance of [mkdocs-material theme](https://squidfunk.github.io/mkdocs-material/) and render it in dark colors.

To have proper syntax highlighting, don't forget to add this code to your `mkdocs.yml` file:

```yaml

markdown_extensions:
    - codehilite:
            guess_lang: False
            use_pygments: True
            noclasses: True
            pygments_style: monokai
```
