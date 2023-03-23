# Machine Intelligence 2: Unsupervised Learning - Tutorial Notes #

[![make LaTeX](https://github.com/kashefy/mi2notes/actions/workflows/makefile.yml/badge.svg)](https://github.com/kashefy/mi2notes/actions/workflows/makefile.yml)
[![Build Status](https://app.travis-ci.com/kashefy/mi2notes.svg?branch=master)](https://app.travis-ci.com/kashefy/mi2notes)
[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-sa/4.0/)

This is a collection of notes I've been making for the course [Machine Intelligence 2: Unsupervised Learning](https://www.ni.tu-berlin.de/menue/teaching_activities/all_courses/machine_intelligence_ii/) at the TU Berlin. 
MI 2 is the second part of two consecutive courses on topics in machine learning and artificial neural networks taught by Prof. Klaus Obermayer of the [Neural Information Processing Group](www.ni.tu-berlin.de) at TU Berlin.

Topics covered throughout the course: 
* Principal Component Analysis
* Hebbian learning
* Kernel PCA
* Independent Component Analysis
* Stochastic optimization
* K-means clustering
* Pairwise clustering
* Self-Organizing Maps
* Locally Linear Embedding
* Probability density estimation
* Mixture models & the Expectation-Maximization algorithm
* Hidden Markov Models
* Estimation theory

Also see similar notes for the course [MI1: Supervised Learning course](https://github.com/kashefy/mi1notes/)

See [Releases](https://github.com/kashefy/mi2notes/releases) to download the latest pdf files.

## Instructions on compiling the LaTeX sources ##

Ubuntu 18.04:

    apt install texlive-fonts-recommended texlive-latex-extra texlive-fonts-extra dvipng texlive-latex-recommended texlive-science texlive-lang-german
    
Additional packages for Ubuntu releases 14.04:
    
    apt install latex-beamer
    
## Contributing ##

Any contribution to add content, visualization and increase the quality of the notes is much appreciated.

Post [Issues](https://github.com/kashefy/mi2notes/issues) to report mistakes (e.g. mistakes in the writing, layout mistakes, problems with referencing)

Making [Pull request](https://github.com/kashefy/mi2notes/pulls) that fix any issues is very much encouraged and appreciated. 
Feel free to make a pull request that resolves an issue with the content and eliminates any mistakes.
Any advice on writing better Latex is welcome as well.
Please keep the scope of changes small to make it easier to spot the differences and identify the contribution in order to speed up the review process and get your changes merges as fast as possible.

For broader changes, open an issue for the proposed broad change so we can discuss it.

## Style ##

At this point I would like to avoid making any major styling changes but open to discussing them.

The notes leave space on the left for your own annotations. You can adjust this space by changing the value for the following under latex/minotes.cls. The changes will apply to all sections:

    \newcommand{\mycolumnleft}{0.2} # in the range of 0 to 1 increasing this value leaves more space on the left.


## Acknowledgment ##

Many thanks to Dr. Moritz Augustin, my predecessor in TA'ing this course, for outlining the content of the tutorials and providing me with his own notes.
