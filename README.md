# generic_rmarkdown_article

The repository consists of a `skeleton.Rmd` skeleton file, a
`template.tex` pandoc template file that is very close to the default
pandoc latex template, and a bunch of pandoc template
partial files. Several of these partial files are empty (`after-body-partial.tex`,
`before-body-partial.tex`). I have only included them as it seemed
like a good thing to do. The others include my code for adding
functionality to the default pandoc latex template for scientific
articles.

Multi-lingual abstracts are working very poorly currently due to a
number of different and separate issues. This needs to be fixed, but
there is currently no simple solution.

For convenience, I am also including a single file
`skeleton_standalone.Rmd` that includes the `template.tex` with the
partials incorporated in the skeleton so you can use it as a
standalone document (but it doesn't include the `.csl` and the `.bib` files). 
