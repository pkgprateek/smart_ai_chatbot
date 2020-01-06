## Description
This is a self learning chatbot. The program will go to a specific website (related to diabete in the presented case)
scrap the info from website and learn from it. When the user writes a query to the chatbot,
it will take that query and find the most similar text from the website we scraped and learned
and respond back with that sentence.

## Packages & Setup
```
conda create -n smartbot python=3.7
conda activate smartbot
conda install numpy scikit-learn jupyter nltk
```

## Newpaper Package
#### For more info visit: https://github.com/codelucas/newspaper/
```
conda install -c conda-forge newspaper3k
jupyter notebook
```
