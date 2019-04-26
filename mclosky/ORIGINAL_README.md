This is my own parsing division of the GENIA 1.0 trees.  The trees
come from:

    http://www-tsujii.is.s.u-tokyo.ac.jp/GENIA/home/wiki.cgi?page=GENIA+Treebank

after having been converted to PTB trees by Illes Solt at Budapest
University of Technology and Economics:

    http://categorizer.tmit.bme.hu/~illes/genia_ptb/

The trees were not immediately readable by the Charniak parser and I have
performed various steps of normalization and cleanups.  I've included
the PMIDs of each division in *.pmids files.

Basic statistics:

Articles:
148  dev
150  test
1551 train
150  future use
---------------
1999 total

Trees:
1361  dev
1360  test
14326 train
1494  future_use
----------------
18541 total

Please email me if you have any questions or suggestions (dmcc@cs.brown.edu)

-- David McClosky (6.16.2009)

Release history:
6.16.2009   Initial release
