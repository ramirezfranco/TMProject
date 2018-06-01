# Text Mining in Public Policy - Final Project
## Jorge Quintero & Jesús Ramirez

[Slides are here](https://docs.google.com/presentation/d/1w-MK5P4YqIqCebr4cmX_qGkueTwD1-5gl5mLH0jSFAI/edit?usp=sharing)

### Main files are: 

* File `PCA.ipynb` has the PCA, LDA, LDiA analyses of the three candidades corpora.
* File `amlo_over_time.ipynb` Analysis of speech of Lopez 2012 - 2018
* File `Similarity_across_candidates.ipynb` Compute similarite metrics and creates plots
* File `Terms.ipynb` Extract the most common terms (words) of the topics.

### Files that download speeches:

* `Meade.ipynb`, `amlo_texts.ipynb` and `Anaya_texts.ipynb` download and pre-process speech data. Eliminates stopwords, some meade-specific meaningless words, lower cases it, etc. Produces a `.csv` file to be used by PCA. File `util.py` is a utility file used by `Meade.ipynb`.

### Data files:

* Downloaded data is stored into individual `.csv` files. `svd.csv` is used in `amlo_over_time.ipynb`