# A Survey on Mahine Learning Assisted Heuristic Search for Combinatorial Optimization Problems
This repository contains the sources for the summary table of our survey, available online at https://yangmingzhou.github.io/Survey/

## Compiling

The main source is `summary.tex`. Compile it with LaTeX, then run bibtex, which
will pick up the references in `survey.bib`. This will generate the document
with the table.

To generate the web version, go to the `web/` subdirectory and run `run.sh`.
This will update `lit.json`. `index.html` should be updated manually with the
last modified date as appropriate.

## Modifying

To add new references, add the bib entry to `survey.bib` and a new entry in the
table in `summary.tex` using the format that the other entries use. Please try
to keep the descriptions in the columns short and use terms that already exist
if possible so that the entries group together nicely.

## Citing

If you find this reference useful, please cite

## Contributors

