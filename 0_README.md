Name: Biz Herman
Date: 11 August 2016

## Overview

This project provides code to carry out topic modeling, polarity, and discriminating word analysis for the speeches given at the Republican National Convention (RNC) and Democratic National Convention (DNC). This can be applied to any collection of speeches, in order to identify trends in the topics covered.

## Dependencies

This code depends on the following software:

1. R, version 3.1

There are a number of packages that need to be installed in the R code, including:

1. tm
2. RTextTools
3. qdap
4. qdapDictionaries
5. plyr
5. dplyr
6. ggplot2
7. SnowballC
8. mallet
9. wordcloud
10. RColorBrewer
11. data.table
12. scales

## Files

#### Data

1. rncFINAL.csv: Contains transcripts from all RNC speehces.
2. dncFINAL.csv: Contains transcripts from all DNC speeches.
3. stoplist.csv: Common words used that are eliminated from the documents when modeling topics.

#### Code

1. RNCDNCcode: Conducts topic modeling, polarity, and discriminating word analysis on speeches. Includes visualizations of all analyses using wordclouds.

## More Information

Code developed using code from Rochelle Terman's PS239T course, taught at UC Berkeley in Fall 2015. Github repository available <a href="https://github.com/rochelleterman/PS239T">here</a>.

To get in touch, please write elizabethdherman@gmail.com or visit www.bizherman.com!
