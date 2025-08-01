# corpora-descriptives

The goal of this Repo is to outline the descriptive information from 51 NLTK corpora.
This provides users with information regarding the average word count change after stop words removed and average word counts.


## Table: Corpus Word Counts
|    | corpus                |   word_count |   word_count_without_stopwords |   percentage_removed |
|---:|:----------------------|-------------:|-------------------------------:|---------------------:|
| 18 | jeita                 |      3254399 |                        3250655 |            0.115044  |
| 15 | gutenberg             |      2621613 |                        1505565 |           42.571     |
|  7 | comtrans              |      1978268 |                        1643819 |           16.9062    |
| 31 | reuters               |      1720901 |                        1258365 |           26.8775    |
| 22 | movie_reviews         |      1583820 |                         875409 |           44.728     |
| 20 | mac_morpho            |      1170095 |                         953771 |           18.4877    |
|  2 | brown                 |      1161192 |                         674660 |           41.8994    |
| 23 | multext_east          |      1054921 |                         955219 |            9.45113   |
| 48 | udhr2                 |       926859 |                         883679 |            4.65875   |
| 32 | semcor                |       820411 |                         479739 |           41.5246    |
|  0 | abc                   |       766811 |                         470377 |           38.658     |
|  9 | conll2002             |       678377 |                         606108 |           10.6532    |
| 21 | masc_tagged           |       592536 |                         375761 |           36.5843    |
| 47 | udhr                  |       585240 |                         552477 |            5.59822   |
|  3 | cess_cat              |       503853 |                         443160 |           12.0458    |
| 30 | pros_cons             |       420182 |                         336460 |           19.9252    |
| 35 | state_union           |       399822 |                         228730 |           42.792     |
| 49 | webtext               |       396733 |                         275232 |           30.6254    |
| 14 | genesis               |       315268 |                         261219 |           17.1438    |
|  8 | conll2000             |       259104 |                         171750 |           33.7139    |
| 37 | subjectivity          |       240576 |                         137278 |           42.9378    |
| 50 | words                 |       236736 |                         236315 |            0.177835  |
| 33 | sentence_polarity     |       224073 |                         128187 |           42.7923    |
| 12 | floresta              |       211852 |                         172250 |           18.6932    |
| 39 | swadesh110            |       202340 |                         201286 |            0.520905  |
|  4 | cess_esp              |       192686 |                         170119 |           11.7118    |
| 16 | inaugural             |       156288 |                          79952 |           48.8432    |
| 10 | conll2007             |       145156 |                         133510 |            8.02309   |
|  6 | comparative_sentences |       142770 |                          80299 |           43.7564    |
|  1 | alpino                |       139820 |                         125994 |            9.88843   |
| 40 | swadesh207            |       139672 |                         139045 |            0.448909  |
|  5 | cmudict               |       133737 |                         133199 |            0.402282  |
| 46 | treebank_raw          |       101794 |                          68927 |           32.2878    |
| 44 | treebank              |       100676 |                          69400 |           31.066     |
| 45 | treebank_chunk        |        94200 |                          62906 |           33.2208    |
| 11 | dependency_treebank   |        94084 |                          62808 |           33.2426    |
| 34 | sinica_treebank       |        91634 |                          91634 |            0         |
| 29 | product_reviews_2     |        84619 |                          48438 |           42.7575    |
| 41 | switchboard           |        82792 |                          49466 |           40.2527    |
| 28 | product_reviews_1     |        73832 |                          38300 |           48.1255    |
| 19 | knbc                  |        66952 |                          66952 |            0         |
| 17 | indian                |        48754 |                          48754 |            0         |
| 26 | nps_chat              |        45010 |                          31301 |           30.4577    |
| 36 | stopwords             |        11009 |                          10326 |            6.20401   |
| 24 | names                 |         7944 |                           7944 |            0         |
| 27 | opinion_lexicon       |         6789 |                           6783 |            0.0883783 |
| 25 | nonbreaking_prefixes  |         5203 |                           5142 |            1.1724    |
| 38 | swadesh               |         4935 |                           4840 |            1.92503   |
| 42 | timit                 |         1394 |                            742 |           46.7719    |
| 13 | gazetteers            |         1211 |                           1211 |            0         |
| 43 | timit_tagged          |         1079 |                            577 |           46.5246    |

## Corpora Descriptives
```
number of corpora in NLTK 51
mean percentage removed 21.91
word count mean 476,471.02
```
We can see 397 unique stop words from NLTK and scikit-learn's collections.
```
Total number of unique stopwords from NLTK and scikit-learn: 397
```

From this, we can see the most common stop words being removed. This can help users to decide which stop words are most important to remove.
We can see from this top 20 list that the difference between the top 5 is considerable to the bottom 5. Therefore, it may be that appending lists of stop words has little effect.



## Table 2 Most Frequent Stop Words
|    | word   |   count |
|---:|:-------|--------:|
|  0 | the    |  583,580 |
|  4 | a      |  347,732 |
|  1 | of     |  321,415 |
|  3 | and    |  293,456 |
|  2 | to     |  282,264 |
|  5 | in     |  217,607 |
| 20 | de     |  198,037 |
|  6 | is     |  124,672 |
|  7 | that   |  117,080 |
|  9 | for    |   93,184 |
| 11 | it     |   91,011 |
| 41 | o      |   78,672 |
| 16 | with   |   67,409 |
| 35 | as     |   58,344 |
| 14 | on     |   57,387 |
| 12 | be     |   56,757 |
| 21 | was    |   51,592 |
| 19 | he     |   49,513 |
| 36 | his    |   44,172 |
|  8 | s      |   43,418 |
