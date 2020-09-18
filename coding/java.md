# Java

## \(JV-100\) `.gitignore`

Requirements:

* All repositories _must_ include a `.gitignore` file the root of the `main` branch. This file should include all of the items in the GitHub default as well as the following:
```
javadocs
target
```

Rationale:

* Source repositories should _only_ contain source files and rarely files that can be generated. Any files that can be generated, should be generated at build or deploy time.

Exceptions:

* None


## \(JV-200\) Published JavaDocs

Requirements:

* All repositories should have a link in the `README.md` document that directs readers to the published JavaDocs.

Rationale:

* Easy access to JavaDocs is crucial for understanding the functionality of an application.

Exceptions:

* None
