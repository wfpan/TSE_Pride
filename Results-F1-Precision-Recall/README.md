# Introduction
This directory contains the results (i.e., Precision, Recall, and F1) obtained on the subject systems using different weighting mechanisms.

Note that, each CSV file contains 19 columns. For example, in the file of [DWM\csv_filter_f1\ant_main_filter_f1.csv], there are 19 columns, i.e., ant_main(10), a-index, 
inDeg, outDeg, allDeg, inWDeg, outWDeg, allWDeg, ForwardBackPageRank-Sora, ForwardPageRank-Sora, inDeg-core, outDeg-core, g-core, g-core-Right, h-index, k-core, LiuPageRank, 
TSEPageRank, and TSEPageRank_v15. The first column (i.e., ant_main(10)) shows the name of the software (i.e., ant) and the number of key classes in the software (i.e., 10). The 
rest 18 columns actually correspond to 18 approaches. Eight approaches are used in this work, while other approaches are only devised by us, but not used in this work. It should 
be noted that the name of the eight used approaches in the CSV file is different from that used in our work. The following Table shows the mapping of the name used in CSV file and 
the name used in our work.

Names in the CSV | a-index | h-index | k-core | ForwardPageRank-Sora | ForwardBackPageRank-Sora | g-core | TSEPageRank | LiuPageRank | TSEPageRank_v15
---- | ---- | --- | --- | --- | --- | --- | --- | --- | ---
Names in this work | a-index | h-index | k-core | PageRank | PageRank_BR | ICOOK | ElementRank | PageRank_IVOL | Pride

# DWM
This directory contains the results obtained on the subject systems using DWM weighting mechanism.

## csv_filter_f1|precision|recall
These directories contain the results using filtering rules. Specifically, csv_filter_f1, csv_filter_precision, and csv_filter_recall contain the f1, precision, and recall results, respectively.

## csv_nofilter_f1|precision|recall
These directories contain the results without using filtering rules. Specifically, csv_nofilter_f1, csv_nofilter_precision, and csv_nofilter_recall contain the f1, precision, and recall results, respectively.

# OWM
This directory contains the results obtained on the subject systems using OWM weighting mechanism.

## csv_filter_f1|precision|recall
These directories contain the results using filtering rules. Specifically, csv_filter_f1, csv_filter_precision, and csv_filter_recall contain the f1, precision, and recall results, respectively.

## csv_nofilter_f1|precision|recall
These directories contain the results without using filtering rules. Specifically, csv_nofilter_f1, csv_nofilter_precision, and csv_nofilter_recall contain the f1, precision, and recall results, respectively.

# EWM
This directory contains the results obtained on the subject systems using EWM weighting mechanism.

## csv_filter_f1|precision|recall
These directories contain the results using filtering rules. Specifically, csv_filter_f1, csv_filter_precision, and csv_filter_recall contain the f1, precision, and recall results, respectively.

## csv_nofilter_f1|precision|recall
These directories contain the results without using filtering rules. Specifically, csv_nofilter_f1, csv_nofilter_precision, and csv_nofilter_recall contain the f1, precision, and recall results, respectively.
