# Named Entity Recognition

Your task is to develop a named entity recognition model on the English portion of the [CoNLL'03 shared task](https://www.clips.uantwerpen.be/conll2003/ner/) dataset:

* Training set: [conll03.eng.trn.tsv](res/conll03.eng.trn.tsv)
* Development set: [conll03.eng.dev.tsv](res/conll03.eng.dev.tsv)
* Evaluation set: [conll03.eng.tst.tsv](res/conll03.eng.tst.tsv) (unlabeled)

The followings describe the format of the dataset:

* The first and the second columns indicate token forms and their named entity tags, respectively.
* The named entity tags use the [BILOU](http://www.aclweb.org/anthology/W09-1119) notation to distinguish chunk boundaries.
* Each sentence is delimited by a blank line.

## Task 1

* Clone this repository.
* Download the 100 dimensional word embeddings trained by FastText: https://s3.amazonaws.com/elit-public/resources/embedding/fasttext-100-180614.bin