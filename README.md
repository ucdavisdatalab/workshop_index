# UC DataLab Workshop Index

_[UC Davis DataLab](https://datalab.ucdavis.edu/)_  
_Maintainer: Nick Ulle <<naulle@ucdavis.edu>>_

* [Reader](https://ucdavisdatalab.github.io/workshop_index)


## Contributing

The course reader is a live webpage, hosted through GitHub, where you can enter
curriculum content and post it to a public-facing site for learners.

To make alterations to the reader:
	  
1.  Check in with the reader's current maintainer and notify them about your 
    intended changes. Maintainers might ask you to open an issue, use pull 
    requests, tag your commits with versions, etc.

2.  Run `git pull`, or if it's your first time contributing, see
    [Setup](#setup).

3.  Edit the `index.qmd` Quarto Markdown file. Enter your text, code, and other
    information directly into the file.

    Put any supporting resources in `data/` or `images/`. Store large files in
    Google Drive or other cloud storage rather than committing them to the
    repo. You do not need to add generated resources (such as HTML files). The
    render step saves these in `docs/` automatically.

4.  In a terminal, navigate to the this repo and run `quarto render` to
    re-render the website (the files in `docs/`).

5.  When you're finished, `git add`:
    - Any files you added or edited directly, including in `data/` and
      `images/`
    - `docs/` (all of it)

    Then `git commit` and `git push`. The live web page will update
    automatically after 1-10 minutes.


<!--
### Github Actions

GitHub Actions can be set up to automatically render your reader when you push 
new content to a repo. If you would like to use this function, download the 
materials in [datalab-dev/utilities/render_bookdown_site][render-site] and 
follow the instructions there.

[render-site]: https://github.com/datalab-dev/utilities/tree/main/render_bookdown_site
-->

## Setup

This project uses [Quarto][]. Make sure it is installed before rendering the
website.

[Quarto]: https://quarto.org/

[Back to Top](#top)
