# TSE_Pride
This is the replication package for our work accepted by IEEE Transactions on Software Engineering, i.e., Weifeng Pan, Hua Ming, Dae-Kyoo Kim, Zijiang Yang. PRIDE: Prioritizing documentation effort based on an improved PageRank algorithm and simple filtering rules. IEEE Transactions on Software Engineering, 2023, 49(3): 1118-1151. DOI: 10.1109/TSE.2022.3171469. [[PDF](https://ieeexplore.ieee.org/document/9765699)]

# WDCCN
This directory contains the WDCCNs that we built for all the subject systems used in our experiments. There are three versions of WDCCNs according to different weighting mechanisms.

# Pride.jar
Pride.jar is the tool used to compute the ClassRank PageRank values. It is a small part of our own developped software, SNAP. Of course, the SNAP software can be obtained by emailing us (Email: wfpan@zjgsu.edu.cn).

# How to use our data set and software
The steps to use Pride.jar is shown as follows. To run the software, you should install the jdk (java development kit) 1.6 (or higher) first in your computer. JDK can be downloaded from https://www.oracle.com/technetwork/java/javase/downloads/index.html
- Download the Pride.jar and the data set file to the same directory.
- Double-click the Pride.jar
- Select File->Open a WDCCN file...
- Browse the WDCCN directory and select a specific WDCCN file (end with .net).
- Select Analysis->ClassRank
- Then you will get the ClassRank PageRank value for each class. You can also find a file storing the obtained results in the corresponding directory.

# Cite our work
If you use our data set or tool, please cite our work.

Weifeng Pan, Hua Ming, Dae-Kyoo Kim, Zijiang Yang. PRIDE: Prioritizing documentation effort based on an improved PageRank algorithm and simple filtering rules. IEEE Transactions on Software Engineering, 2023, 49(3): 1118-1151. DOI: 10.1109/TSE.2022.3171469. [[PDF](https://ieeexplore.ieee.org/document/9765699)]
