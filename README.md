# Filmweb+

Filmweb+ is a dataset of Polish movie reviews used in a work *"Sentiment Classification using Machine Learning"* by Paweł Narolski for the purpouse of a document-level sentiment classification task.

It contains `27202` reviews in total, which are divided into `unlabelled`, `positive`, `neutral` and `negative` classes based on rating given by the review's author.

| Class (indice)  | # of reviews |
|-----------------|--------------|
| Unlabelled (-1) | 7710         |
| Negative (0)    | 3085         |
| Neutral (1)     | 9436         |
| Positive (2)    | 6971         |

Reviews have been fetched from `Filmweb`, `Film.org.pl`, `Kinoblog`, `FDB` and `blogfilmowy24`. They contain an average of `514` words (or `3582` characters) per document.

The dataset has been pre-processed in order to remove unnecessary `HTML` tags or other redundant metadata, such as image descriptions, using the [Spacey](https://github.com/maxster256/spacey) preprocessor.

## Document-level Sentiment Classification Results

A `ULMFiT`-based document level sentiment classification system proposed in work *"Sentiment Classification using Machine Learning"* (Narolski, 2020) has achieved a state-of-the-art result of 94,19% for Polish document-level sentiment classification task for a corpora of long, real-world text documents, with over 500 words per document on average.

## Citation

If you've found this dataset helpful for your work, please consider citing the work *"Sentiment Classification using Machine Learning"* (Narolski, 2020) or providing an appropriate authorship attribution.



