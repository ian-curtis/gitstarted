# Better Git Started: An Introduction to the Command Line, GitHub, and Git

*Better Git Started* is a work designed for users who have little to no experience with using or interacting with a terminal or with Git/GitHub. The book first introduces readers to basic computer ettiquette and basics such as file name guidelines and other recommended practices. Then, the command line is introduced and basic commands are taught. Following that is a discussion of GitHub and Git for those working alone and then for those working in a team.

No experience is necessary to read this book; everything is taught in order and starts from the beginning. Necessary materials are explained in a preface and a GitHub account is created as part of the regular book activities. The book works sequentially with activities that build off of each other and require the reader to follow along with their own computers, giving direct examples of the content given.

## License

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit [the Creative Commons website](http://creativecommons.org/licenses/by-sa/4.0/).

![CC-BY-SA logo](assets/cc_by_sa.svg)

## Compilation and Build Instructions

The HTML version of the book is hosted on [GitHub Pages](https://ian-curtis.github.io/gitstarted/frontmatter.html). PDF files for both electronic and print platforms can be found in the `output` directory along with their corresponding LaTeX files (note that these files are not meant to be user friendly).

*Git Started* was written in PreTeXt (https://pretextbook.org), a markup language designed for authors. Thus, to edit and build the book yourself, you will need to use PreTeXt.

Make sure you have Python, LaTeX (if making a PDF), and a good text editor installed. Fork, then clone this repository with

```
git clone https://github.com/ian-curtis/gitstarted.git
```

and install PreTeXt on the command line using Python

```
pip install pretext==1.0.2
```

To build the HTML, type `pretext build html` and then `pretext view html` on the command line. For PDF builds, use either `pretext build latex-elec` or `pretext build latex-print` and use your LaTeX installation to compile a PDF.

## Abbreviated Publisher's Note

*Better Git Started: An Introduction to the Command Line, GitHub, and Git* was written by Ian Curtis, a senior at Grand Valley State University and Editorial Assistant for the GVSU Libraries. This text was developed as part of the [Accelerating Open Educational Resources Initiative at Grand Valley State University](https://www.gvsu.edu/library/sc/AcceleratingOER), with support from the University Libraries and the President's Innovation Fund.

 Suggested Attribution: *Better Git Started: An Introduction to the Command Line, GitHub, and Git*, by Ian Curtis, published by the Grand Valley State University Libraries, 2022.

### Accessibility Statement

The Grand Valley State University Libraries strive to ensure our tools, devices, services, and environments are available to and usable by as many people as possible.

The web version of *Better Git Started* incorporates the following features to support accessibility:

* All content can be navigated by use of a keyboard
* Links, headings, and tables have been designed to work with screen readers
* Code in PreTeXt is rendered with separate blocks so they can be understood by using screen readers and/or other assistive devices.


## Questions?

With any questions, comments, concerns, feature requests, and more, be sure to open an issue. If you are feeling up to it, do some editing and submit a pull request, especially if you wish to add content to the sections on Linux.
