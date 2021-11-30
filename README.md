# LaTeX template

You can use this template to format your thesis document using LaTeX. It folows the APA style with some customizations. It's based on the [Swiss Federal Institute of Technology in Lausanne (EPFL) PhD Thesis](https://www.overleaf.com/latex/templates/swiss-federal-institute-of-technology-in-lausanne-epfl-phd-thesis/dhcgtppybcwv) template available in Overleaf.

# Installation

You need a standard LaTeX distribution:

- Windows: MikTeX
- Mac OS X: MacTeX
- Linux: TeXLive

and a LaTeX editor like TexMaker or Visual Studio Code. You can also use Overleaf after cloning or forking this repository.

# Testing and using

The template is organised in three subfolders and a couple of additional files. 

- main.tex: This is the main document and it includes all other files. Probable you don't need to change anything unless you want to customise the template.
- settings.tex: Importng packages and configuration. Probable you don't need to change anything unless you want to customise the template.
- head: COntais the files used in the front matter of the document
    - thesistitle.tex
    - thesisinfo.tex
    - dedication.tex
    - acknowledgments.tex
- chapters: COntais the files used in the main matter of the document
    - ch1-xxxx.tex
- back: COntais the files used in the back matter of the document
    - biblio.tex
    - appendix.tex
    - references.bib: BibTeX database with all your references.

Start by creating a new fork of this repository. Replace the content of each chapter and fill other sections as needed. There are some examples on how to include figures, tables and algorithms in some sections. \
