#  Latex prototype

Simple minimal latex file we use for project seeds and papers.

* Most packages are listed but not loaded, to improve compiling speed.

* Latex does not care about certain whitespace. I recommend you use one sentence per line in the `.tex`, which makes editing and git version control much easier.

* The `.gitignore` file is a general-purpose one for all my projects, including python and MS Word files.

* There is a GitHub action to compile in a GitHub container, contained in `.github`. You may wish to omit this for your project.

* Latex/bibtex can handle multiple `.bib` files. For collaborative projects, I recommend each auther makes their own `_myname.bib`. Duplicates will cause problems, but we can fix this at the very end.  
