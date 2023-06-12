# Chapter on Group Concept Mapping

[![CC NA SA 4.0 Logo](https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

This work is part of [Research Methods for Learning Engineers](https://github.com/theResearchMethodsBook/). Any repurposing of this work requires a reference of the parent project. 

## Getting started

1. Install quarto on you system. Please follow the instructions on https://quarto.org/installation.html
2. Clone this repository to your deskop
3. Start editing the chapter.qmd file 
4. Edit the file chapter.qmd with your favourite editor
5. Commit and push your changes to GitHub once you are done. Please commit and push your changes regularly.

## How to organise your chapter

The following files are mandatory:

- `chapter.qmd` - contains the text of your chapter.
- `references.bib` - contains the references of your chapter.
- `authorinfo.qmd` - contains the information about the author(s) of the chapter. If your chapter has multiple authors, please create one authorinfo.qmd file for each author.
- `examples.qmd` - contains the examples of your chapter. If your chapter has multiple examples, please create one examples.qmd file for each example.

Optional files and resources:

- Figures and images are organised in the folder `figures`. This folder contains the EATEL Logo, which is only present for providing the folder. Once you added your own figures and images you can savely delete the EATEL logo.
- Data files are organised in the folder `data`. This folder has to be created by the you, if datasets are shared.

**Important**: Your chapter contains two additional files: `index.qmd` and `_quarto.yaml`. ***DO NOT EDIT OR DELETE EITHER OF THESE FILES!*** They are used to compile the book. Any changes you add to either file will be ignored.

## Chapter requirements

A chapter has to be between 2500 and 5000 Words (approx. 5-10 pages). The chapter is required to be written in English and should be written in a way that it is understandable for a audience that is currently studying for a BSc., MSc. or at PhD students. 

It is recommended to use `quarto` in RStudio or Visual Studio Code. If you use RStudio, please install the `quarto` package from CRAN. If you use Visual Studio Code, please install the `quarto` extension from the Visual Studio Marketplace.

A chapter must have an abstract, a list of keywords, and at lease two references. The abstract should be between 200 and 350 words. The list of keywords should contain between 3 and 5 keywords.

The last line of the chapter must be `## References {-}` and must be followed by a blank line. The references must be in BibTeX format and must be stored in the file `references.bib`.

## Feedback from the editors and reviewers

All feedback is communicated via GitHub issues. Please check the issues of your chapter regularly and respond to the feedback. If you have questions regarding the feedback, please use the comments in the issues to ask your questions.

If you responded to the feedback and consider one issue complete please close the issue. 

## Technical considerations

The book is written in Markdown and is compiled to HTML and PDF using the `quarto` package. 

For local testing you need to install quarto on your computer. Please follow the instructions on the [quarto website](https://quarto.org/install/).

Quarto supports several editors. We recommend to use **RStudio** or **Visual Studio Code**. If you use RStudio, please install the `quarto` package from CRAN. If you use Visual Studio Code, please install the `quarto` extension from the Visual Studio Marketplace. Both editors support live preview of the chapter files.

## License note to authors

The chapter is part of the book and needs to be published under the same license. The license is provided in the file `LICENSE.md`. ***DO NOT CHANGE THE LICENSE OF THE CHAPTER, EDIT OR MOVE THE LICENCE FILE!*** 