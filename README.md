This repository contains a collection of LaTeX snippets that are
hopefully of general use.

Currently, only `biblatex_config.tex` is included, which sets up biblatex
with NLP compatible defaults. With this setup, LaTeX is used with biber and
not with the legacy bibtex.

General tips:
-------------

to make hyperlinks dark blue like in recent ACL publications, add this:

```latex
\usepackage{xcolor}		% make links dark blue
\definecolor{darkblue}{rgb}{0, 0, 0.5}
\usepackage[colorlinks,allcolors=darkblue]{hyperref}
```

To make the bibliography entries small, add this:

```latex
\AtBeginBibliography{\small}
```

