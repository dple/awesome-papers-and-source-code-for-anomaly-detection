# Awesome papers and Source Code for Outlier Detection


### Distance-based Outlier Detection

1. Local Outlier Factor (LOF)
- Paper: *LOF: identifying density-based local outliers*, https://dl.acm.org/doi/10.1145/335191.335388
- Implementation: sklearn https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.LocalOutlierFactor.html.

2. Density-based Incremental LOF (DILOF)
- Paper: *DILOF: Effective and Memory Efficient Local Outlier Detection in Data Streams*, https://dl.acm.org/doi/abs/10.1145/3219819.3220022
- Implementation: github https://github.com/ngs00/DILOF

3. Cluster-Based Local Outlier Factor (CBLOF)
- Paper: *Discovering cluster-based local outliers*, https://www.sciencedirect.com/science/article/abs/pii/S0167865503000035
- Implementation: github https://github.com/yzhao062/pyod/blob/master/pyod/models/cblof.py

4. Exact-Storm
- Paper: *Detecting Distance-Based Outliers in Streams of Data*, http://delab.csd.auth.gr/~papajim/presentations/files/angiulliCIKM2007Detecting.pdf
- Implementation: https://infolab.usc.edu/Luan/Outlier/CountBasedWindow/DODDS/src/outlierdetection/

5. Approx-Storm 
- Paper: *Detecting Distance-Based Outliers in Streams of Data*, http://delab.csd.auth.gr/~papajim/presentations/files/angiulliCIKM2007Detecting.pdf
- Implementation: https://infolab.usc.edu/Luan/Outlier/CountBasedWindow/DODDS/src/outlierdetection/

6. Abstract-C
- Paper: *Neighbor-based pattern detection for windows over streaming data*, https://dl.acm.org/doi/10.1145/1516360.1516422
- Implementation: 

7. Direct Update of Events - DUE
- Paper: *Continuous monitoring of distance-based outliers over data streams*, https://ieeexplore.ieee.org/document/5767923
- Implementation: https://infolab.usc.edu/Luan/Outlier/CountBasedWindow/DODDS/src/outlierdetection/

8. Micro-Cluster Based Algorithm - MCOD
- Paper: *Continuous monitoring of distance-based outliers over data streams*, https://ieeexplore.ieee.org/document/5767923
- Implementation: https://infolab.usc.edu/Luan/Outlier/CountBasedWindow/DODDS/src/outlierdetection/

9. Thresh LEAP
- Paper: *Scalable distance-based outlier detection over high-volume data streams*, http://people.csail.mit.edu/lcao/papers/icde14.pdf
- Implementation: https://infolab.usc.edu/Luan/Outlier/CountBasedWindow/DODDS/src/outlierdetection/


### Clustering-based anomaly detection methods

1. DenStream
- Paper: *Density-Based Clustering over an Evolving Data Stream with Noise*, https://archive.siam.org/meetings/sdm06/proceedings/030caof.pdf
- Implementation: github https://github.com/issamemari/DenStream 

2. D-Stream
- Paper: *Density-based clustering for real-time stream data*, https://dl.acm.org/doi/10.1145/1281192.1281210
- Implementation: https://github.com/richard-moulton/D-Stream 

3. C-DenStream
- Paper: *C-DenStream: Using Domain Knowledge on a Data Stream*, https://link.springer.com/chapter/10.1007/978-3-642-04747-3_23
- Implementation: https://github.com/MaLL-UFSCar/CDenStream 

4. ClusTree 
- Paper: *Clustering trees: a visualization for evaluating clusterings at multiple resolutions*, http://dx.doi.org/10.1093/gigascience/giy083
- Implementation: github https://github.com/lazappi/clustree

5. MR-Stream
- Paper: *Density-based clustering of data streams at multiple resolutions*, https://dl.acm.org/doi/10.1145/1552303.1552307
- Implementation: github

6. SOStream
- Paper: *SOStream: Self Organizing Density-Based Clustering over Data Stream*, https://link.springer.com/chapter/10.1007/978-3-642-31537-4_21
- Implementation: github

7. CluStream
- Paper: *A Framework for Clustering Evolving Data Streams*, https://dl.acm.org/doi/10.5555/1315451.1315460
- Implementation: github https://github.com/narjes23/Clustream-algorithm 


### One classification based anomaly detection

1. OCSVM
- Paper: *Enhancing one-class support vector machines for unsupervised anomaly detection*, https://dl.acm.org/doi/10.1145/2500853.2500857
- Implementation: sklearn https://scikit-learn.org/stable/modules/generated/sklearn.svm.OneClassSVM.html

2. Deep One-Class Classification
- Paper: *Deep One-Class Classification*, http://data.bit.uni-bonn.de/publications/ICML2018.pdf
Implementation: github https://github.com/lukasruff/Deep-SVDD-PyTorch


### Tree based anomaly detection

1. Isolation Forest
- Paper: *Isolation-Based Anomaly Detection*, https://dl.acm.org/doi/10.1145/2133360.2133363
- Implementation: sklearn https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html 

2. Extended Isolation Forest
- Paper: *Extended Isolation Forest*, https://arxiv.org/abs/1811.02141
- Implementation: github https://github.com/sahandha/eif

3. Robust Random Cut Forest (RRCF)
- Paper: *Robust Random Cut Forest Based Anomaly Detection On Streams*, http://proceedings.mlr.press/v48/guha16.pdf
- Implementation: github https://github.com/kLabUM/rrcf

4. Streaming HS-Tree
- Paper: *Fast Anomaly Detection for Streaming Data*, https://www.ijcai.org/Proceedings/11/Papers/254.pdf
- Implementation: github https://github.com/yli96/HSTree

5. RS-Forest
- Paper: *RS-Forest: A Rapid Density Estimator for Streaming Anomaly Detection*, https://ieeexplore.ieee.org/document/7023377
- Implementation: github https://github.com/shubhomoydas/pyaad


