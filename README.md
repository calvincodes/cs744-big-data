# CS 744 Big Data (Fall 2019)
This repository is a collection of lecture notes, my assignment solutions, and my project repository. Please note, the solutions might not be correct.

## Lecture Slides
The lecture slides were created and used by [Prof. Shivaram Venkataraman](https://shivaram.org/) while instructing this course during Fall 2019. If not archived, the course page can be found [here](http://pages.cs.wisc.edu/~shivaram/cs744-fa19/).

## Paper Reviews
[Click here](https://drive.google.com/open?id=1JDCGvYWI0FHtS5lIRvPAg6eLTAkzAjs2) to view my paper reviews.

## In-Class Discussions
[Click here](https://drive.google.com/open?id=1hgRXBX07hGXPn3nqxEzbZZRbIgsDtfMp) to view my in-class discussions.

## My assignment grades

| Assignment    | Score         | Remarks |
| ------------- | ------------- | ------- |
| 1             | 97/100         | Code part 2: 10/10.<br>Code PageRank: 20/20.<br>Code Partitioning: 10/10.<br>Report Partitioning: 20/20<br>-Comments: good use of data and explanation showing DAG and how partitioning affects the DAG.<br>Report Persist: 17/20<br>- Comments: 10 for reporting results (although I am confused about runtime for wiki data, 5.7 minutes is this only per iteration or per what?) and 7 for explanation (no other backing data used).<br>Report Kill Worker: 20/20.<br>Comments: reported data and very good explanation of why earlier failures were better.    |
| 2             | 56/60         | Code LR Single Mode: 5/5.<br>Code LR Distributed Mode: 10/10.<br>Comments: your terminate_cluster command didn’t work, needed to change that in cluster_utils.sh.<br>Code LeNet: 15/15.<br>Comments: you were supposed to use Keras that comes with Tensorflow, I needed to install Keras to run your code. After that, works correctly.<br>Report LR: 10/10.<br>Comments: Data reported is fine. Would be better to have resource util graph over time rather than a number. It seems strange that async has 0 network. Is there a misconfiguration? Otherwise explanations are fine.<br>Report 1,2,3 nodes LeNet: 8/10.<br>Comments: data reported for 1,2,3 nodes. Please don’t paste screenshots for resource utilization as they are not readable.<br>Report Batch Sizes LeNet: 8/10.<br>Comments: data reported, explanation is good. Again screenshots aren’t readable.    |
| Project - Introduction             | 10/10         | Nice work in defining the various workloads!    |
| Project - Poster Presentation             | 4/5         | None    |
| Project - Final Report             | 47/50         | Would be good to include some summary of results in the introduction. Nice experiments and explanations.    |
