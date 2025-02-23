# Latex Novel Template

This is a template for writing a novel in latex. Because novels are large and often require extra material, the project is in `main/`, leaving other directories here for you to use for outlining and planning.

## Installation

Install LaTeX [here](https://www.latex-project.org/get/) or following your favorite distribution.

## Usage

In `main/` there is a makefile with several commands. You may want to edit it to have the right TITLE and AUTHOR.

- `make`: Compiles a printer-paper PDF of your project `TITLE by AUTHOR.pdf`.
- `make mobile`: Compiles a mobile-friendly PDF of your project `TITLE by AUTHOR (mobile).pdf`
- `make word`: Uses `pandoc` to create a MS Word document of the project. Install Pandoc [here](https://pandoc.org/installing.html).
- `make rtf`: Uses `latex2rtf` to create a rich text format version of your project. `latex2rtf` can be downloaded [here](https://latex2rtf.sourceforge.net/latex2rtf_1_9_14.html) or installed with `brew install latex2rtf` from [Homebrew](https://brew.sh/).
- `make epub`: Makes an epub document, suitable for transferring to E-readers.
- `make clean`: Cleans up all the compilation files.
