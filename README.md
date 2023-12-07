# TAR_Stopping_CP_CLF
Repository for the code of the paper "Combining Counting Processes and Classification Improves a Stopping Rule for Technology Assisted Review" by Reem Bin-Hezam and Mark Stevenson, Findings of ACL: EMNLP 2023.


## Instructions

* All data should be placed in the subfolder named data, which contains subfolders for: rankings, qrels, and text.
* The rankings for all datasets were provided, qrels and text could be downloaded from their corresponding links (as some require access agreements)
* Links for the datasets files:
  * Link to [<u>CLEF datasets</u>](https://github.com/CLEF-TAR/tar)
  * Links to CLEF qrels: [<u>CLEF (2017, 2018, 2019)</u>](https://github.com/dli1/auto-stop-tar) 
    * merge each dataset topics qrels into one file and add them to sub-folder: *data/qrels*
  * Links to TREC datasets and qrels (needs access permission): [TR qrels](https://plg.uwaterloo.ca/~gvcormac/total-recall/2016/qrels/) , [Legal qrels](https://trec.nist.gov/data/legal/10/qrel_leg_int_2010_msg_post.txt).
    * add them to sub-folder: *data/qrels*
    * guidelines on how to get access and usage agreements: [TR](https://plg.uwaterloo.ca/~gvcormac/total-recall/2016/guidelines.html) , [Legal](https://trec-legal.umiacs.umd.edu/)
  * Link to [<u>RCV1 Dataset</u>](http://www.ai.mit.edu/projects/jmlr/papers/volume5/lewis04a/lyrl2004_rcv1v2_README.htm)
    * the tokenized RCV1 documents can be downloaded from section\:B.12.i. RCV1-v2 Token Files, 
    * the qrels can be downloaded from sections B7-B10, merge each dataset topics qrels into one file and add them to sub-folder: *data/qrels*
