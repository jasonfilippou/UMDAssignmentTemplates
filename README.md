# README

The purpose of this repo is to help me with the management of my various *LaTeX*-formatted assignments for CS UMD students.

## CONTENTS

`include/`: A directory of all my included `.tex` files. Those files make up the entirety of the macros that I have found useful and I would like to make readily available by my various projects. Examples:

- `include/mymath.tex` contains many macros useful for courses such as *CMSC250, Discrete Mathematics*. Those macros help with the formatting of quantifiers, negations, as well as the size of symbols and formatting of formulae.

- `include/code.tex` contains a specific configuration of the package [`lstlistings`](https://en.wikibooks.org/wiki/LaTeX/Source_Code_Listings), which is a great package for formatting source code in *LaTeX*. I am likely to use this in coding-heavy courses such as *CMSC420, Data Structures*.

`img/`: A project-specific directory with image files in various common formats (`png`, `gif`, `jpg`, ...).

`README.md`: The current **Markdown**-formatted text file.

`LICENSE`: Copy of the license for this repository.

`.gitignore`: Git ignore file.

`*.{tex,pdf}` (optional): If present, those are:

- *tex* source of an example document that uses the contents of the `include/` and `img/` directories.
- The **pdf** that is compiled when running `pdflatex` on the aforementioned *tex* source.


## LICENSE

Refer to LICENSE file.
