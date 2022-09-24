# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## A new header

```py title="A function" linenums="1" hl_lines="2 3"
def some_function() -> list:
    print("This is how we do it!")
    return 2 + 2 # (1)!
```

1. :material-database: This is an example of a code annotation!


:man_raising_hand: This is a man raising a hand!

:simple-databricks:

Inline Python code highlighting `#!py range()`
