
Tooling for generating OBP's PDF and HTML readers from metadata.

This suite installs the relevant processing tools, and runs them on a
set of three files:

* `book.pdf`
* `book.epub`
* `book.json`

and yields the conventional HTML pages and image output (in odd locations).

To run:

```
    ./setup
    ./run prefix
```

Where `prefix` is the common name for your book files, e.g., `Wolfthal-Pogroms_Ukraine`, entails that you have files `Wolfthal-Pogroms_Ukraine.json`,
`Wolfthal-Pogroms_Ukraine.pdf` and `Wolfthal-Pogroms_Ukraine.epub`

