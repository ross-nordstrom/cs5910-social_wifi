# Proposal

My research proposal on using Social Login for simpler WiFi authentication.

## Overview

The proposal is built using [LaTex](http://www.latex-project.org/). 
The directory is setup so you simply need to edit the text within
the *.tex files, then build a `PDF` with:
```bash
make clean all
```

The `Makefile` makes several passes because of the weird way LaTex works.

### Structure

The file structure:

```bash
 - .gitignore           - tells git to ignore some files produced during the build
 - Makefile             - builds the report
 - sig-alternate.cls    - template defining the structure of the PDF
 - [Paper contents]     - contents of the report
    - proposal.tex                        - main contents of the paper. includes the other files during build time
    - {motivation, ..., conclusion}.tex   - each file represents a section of the paper
    - citations.bib                       - list of citations. In ACM, click "BibTeX" then copy/paste the contents of the popup. These can be referenced by name
```

### Building
  1. Download LaTeX -- e.g. `apt-get install texlive`
  2. `make clean all`
  3. Manually upload the resulting `PDF` to drive or somewhere for sharing or submitting
