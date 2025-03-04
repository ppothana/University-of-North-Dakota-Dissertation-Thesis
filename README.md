# University of North Dakota Thesis/Dissertation LaTeX Template

This repository provides a LaTeX template designed for the creation of University of North Dakota theses and dissertations. The template is structured to offer clarity and flexibility while meeting University of North Dakota theses and dissertations academic formatting standards.
## Disclaimer

This repository is an independent project and is not an official source or endorsement by the University of North Dakota. It is provided solely for academic reference and convenience. Users must verify that the formatting complies with the official guidelines provided by the university.

## Overview

The template includes the following components:

- **Front Matter**: Customizable title page, copyright page, approval page, and permission page.
- **Acknowledgements and Abstract**: Dedicated sections to recognize contributions and summarize research.
- **Contents Management**: Automatic generation of the table of contents, list of figures, and list of tables.
- **Chapter Organization**: A modular approach allowing individual chapter files for easy editing.
- **Bibliography Support**: Integration with BibTeX using the plain bibliography style.

## File Structure

- **main.tex**: The primary document file that compiles the overall thesis/dissertation.
- **chapter1.tex, chapter2.tex, ...**: Example chapter files. Adjust or add files as needed.
- **references.bib**: A sample bibliography file for managing citations.
- **figures/**: A directory intended for all image files referenced in the document.

## Usage Instructions

1. **Prerequisites**  
   Ensure a LaTeX distribution (e.g., TeX Live, MikTeX, or MacTeX) is installed. The template depends on packages such as `amsmath`, `graphicx`, `natbib`, `geometry`, among others.

2. **Compilation**  
   Use your preferred LaTeX editor or command-line tool. A typical compilation sequence is as follows:
   ```bash
   pdflatex main.tex
   bibtex main
   pdflatex main.tex
   pdflatex main.tex
