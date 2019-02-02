
## **Universal Dependencies v1.0 for the GENIA Treebank.**
-----------------------------------------------------


## What is in this repository?

This repository contains several pieces of data related to the GENIA Corpus.


* The original GENIA Corpus distribution, found in `original_data`. This is in it's original XML format and contains Constituency and Part of Speech tag information.

* David Mclosky's distribution of the GENIA Treebank in the Penn Treebank format in the  `mcklosky` directory.

* A version of David Mclosky's splits of the GENIA dataset converted to Universal Dependencies v1.0 using the Stanford Dependency Converter. Note that this conversion process is not 100% reliable. These files are distributed in the `conllu` format and can be found at the root of the repository: `train.conllu, dev.conllu, test.conllu, future_use.conllu`.

* `raw/` - This directory contains the untokenized text for each Pubmed abstract. Each file in this directory is of the form `{pubmed id}.txt`.

* `pubmed_metadata/` - This directory contains the full, unedited metadata from the pubmed abstracts which was stripped in the original distribution. In particular, it contains author information, publication statistics, citation statistics and abstract level entity information, which is linked to MeSH.

* *_per_sentence.pmids - These files contain the pubmed id for each sentence in the respective *.conllu file. These can be used to align the sentences with dependency annotations to their raw sentences in the `raw/` directory.