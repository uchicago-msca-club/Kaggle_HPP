# Kaggle_HPP
https://www.kaggle.com/c/house-prices-advanced-regression-techniques


The notebooks will be continuously updated by completing the ToDo sections.

When a notebook is updated, your forked repo will have to be updated using the following procedure - 

## Case 1 - No changes in local repo / Unconflicting changes in local repo

1. Open a terminal in the main folder of forked repo
1. Type the command <b>git pull https://github.com/uchicago-msca-club/Kaggle_HPP.git</b>
1. <b>push</b> the changes using Github desktop or typing <b>git push</b> in the terminal

NOTE : Unconflicting changes are essentially changes to the code in your forked repo that exist independently of the code written in main repo

## Case 2 - Conflicting changes in local repo

1. Open a terminal in the main folder of forked repo
1. Type the command <b>git pull https://github.com/uchicago-msca-club/Kaggle_HPP.git</b>
1. If the conflicting file is a .py file or a .md file, you can use notepad++ or VSCode to fix it easily.
1. If the conflicting file is a .ipynb, use notepad++ to find a sequence of <b>>>>></b> symbols, and choose the favored code snippets between HEAD and LOCAL sections
1. Once codes are chosen, delete the <b>>>>> HEAD</b> and <b><<<< ... </b> lines, and save the file
1. <b>commit</b> the changes
1. <b>push</b> the changes using Github desktop or typing <b>git push</b> in the terminal
