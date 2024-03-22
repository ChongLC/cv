This is a repo of generating a LaTeX CV via R Markdown. Inspired by [cv from jacob-long](https://github.com/jacob-long/cv) and further modified to suit my individual needs.

`cv-simple.tex` is the pandoc template used by `cv.Rmd`. It, in turn, uses the `simplecv` class defined by `simplecv.cls`, a version of Zach Scrivena's `simple-resume-cv`[https://github.com/zachscrivena/simple-resume-cv]. While the template has been extensively modified, you can still observe the basic structure, particularly the section headings in the left margin.

## Usage
To generate the PDF CV, you can use the `rmarkdown::render()` function directly from within R or use the `make` command from the command line as a shortcut.
