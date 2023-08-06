QCB Thesis Template - TeX
=========================

TeX template for the master's thesis in [Quantitative and Computational Biology](https://offertaformativa.unitn.it/en/LM/quantitative-and-computational-biology), 
[CIBIO department](https://www.cibio.unitn.it/), [University of Trento](https://www.unitn.it/).

- Guidelines version: [2020](https://offertaformativa.unitn.it/en/lm/quantitative-and-computational-biology/graduation)
- Academic year revision: 2022-2023

__NOTE__: The guidelines would require the typeface to be set to Times New Roman. I cannot get it to work, no matter how many stack threads I read. If you know how, please let me know or open a pull request. I still believe that is just to prevent people from using unreasonable typefaces, thus I do not consider it top priority.


Overleaf usage
--------------

- Download the entire directory as a .zip file or clone it and then zip it.
- In Overleaf press `New Project > Upload Project` and then select the .zip file.
- Work normally in Overleaf. You can remove `README.md`, `build` folder and `buildlatex`


Local usage
-----------

- [Install](https://www.latex-project.org/get/) LaTeX and additional libraries if required. On Ubuntu 22.04, all required libraries can be installed using the commands `sudo apt install texlive-latex-extra -y` and `sudo apt install texlive-font-utils -y`
- Clone the repository using `git clone https://github.com/StefanoCretti/QCB_thesis_TeX_template`
- Modify as per requirements.
- Navigate to the directory `cd ./SOME_PATH/QCB_thesis_TeX_template`
- Compile to pdf using `sh buildlatex principal.tex`. The `buildlatex` script is a slightly modified version of the one on Giacomo Fantoni's [Github page](https://github.com/giacThePhantom/my-scripts/blob/master/buildlatex). The compiled file will be at `./build/principal.pdf`.
