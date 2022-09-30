**2021 March Madness Predictor README**

All roughly 200-300 lines of code in the dataiku.ipynb were written by me, and all csv files were scraped by me from public sites. All is usable by anyone wishing. The Bracket_builder csv includes the win percentage of every game possible in the 2021 march madness tournament, with which you can easily make your bracket. Quick editing of the code and some scraping would allow this code to be used for next year as well. The code is somewhat out of order, as I ran it line by line, but with comprehension of pandas modeling it would not be hard to fix.

The project utilizes pandas, polynomial regression, kvfolding, lasso, pca, and other modeling techniques to limit overfitting and provide for feature selection. The results were used to make a bracket on ESPN that scored in the 99th percentile.
