# tifr-thesis

This package provides all the files needed to support the production and typesetting of a PhD dissertation at TIFR though it can easily be adapted to meet the requirements of other schools. The format and styling is based closely on the requirements published by each university's registrar.


## Getting started
1. Install LaTeX. For Mac OS X, we recommend MacTex (http://tug.org/mactex/); for Windows, MiKTeX (http://miktex.org/); and for Ubuntu, Tex Live (`sudo apt-get install texlive-full`)
2. Install the default fonts: EB Garamond, Lato, and Source Code Pro. The files are provided in `fonts/EB Garamond`, `fonts/Lato`, and `fonts/Source Code Pro`.
3. Personalize the document by filling out your name and all the other info in `frontmatter/personalize.md`.

4. Set the correct if variables in `ifs.tex`. Setting the public variable to true will remove the tifr logo, declaration and synopsis (which you might want to use for puting up online). Setting scanneddeclaration to true, will insert the `declaration.pdf` document (where you can keep a scanned copy of this page with yours and your advisors signature). Setting the nosynopsis to false will result in insertion of `synopsis.pdf` and adding entries for THESIS and SYNOPSIS in the toc. 

5. Build your dissertation with `build.command`, located in the `scripts` directory (e.g., you can `cd` into the main directory and then run `./scripts/build.command`).

## FAQ

### How do I make the text justified instead of ragged right?
Remove or comment out the line `\RaggedRight` from the .cls file.

## Acknowledgments

This is just a modified version of the ausome template by Jordan Suchow (https://github.com/suchow/Dissertate)

