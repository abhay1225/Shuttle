# Shuttle
This is  an explanation on the approach to shuttle data(NASA)

## Problem Statement:
Detect if there is an anomaly in the radiator of a NASA Space Shuttle at a given point of time by taking the conditions of radiator into consideration.
## About Anomaly Detection:
Anomaly detection is a technique used to identify unusual patterns that do not conform to expected behaviour. It has many applications in business, from intrusion detection (identifying strange patterns in network traffic that could signal a hack) to system health monitoring (spotting a malignant tumour in an MRI scan), and from fraud detection in credit card transactions to fault detection in operating environments.
## Data Description:
The dataset shuttle has 58,000 data points; 43,500 for training and 14,500 for testing. There are 9 attributes and 1 target variable. The Id variables is the different instances of Time.
The target variable contains 7 classes: 
    1.	Rad Flow 
    2.	Fpv Close 
    3.	Fpv Open 
    4.	High 
    5.	Bypass 
    6.	Bpv Close 
    7.	Bpv Open
    
These classes indicate the various actions that can be taken regarding the radiator. Adjusting the Radiation Flow is a normal action and hence constitutes to 78.4% of the data, the rest are actions that are taken under abnormal conditions.
Acronyms – Rad Flow (Radiator flow), FPV (flow proportioning valve), BPV (bipropellant valve)

The data was released by NASA. The 9 attributes concern the condition of radiators in a NASA space shuttle. This is a Realtime data collected during an actual space shuttle flight. Data was designed to study the supervised anomaly detection. 
The Training set contains 78.4% data of Class 1 (Rad Flow). The Class 1 (Rad Flow) can be taken as the Normal Class. Besides the Normal Rad Flow Class, about 21.6% of the original data describe abnormal situations. Class 2, 3, 4, 5, 6, 7 can all be classified as an Anomaly.

Here, we are more concerned about increasing the Recall – and the rate of increase in TPR/Recall should be more than the rate of increase in the FPR.
# Acknowledgements
Thanks to NASA and UCI for providing this dataset.

Source: http://archive.ics.uci.edu/ml/datasets/Statlog+(Shuttle)

# Papers That Cite This Data Set: 
Ira Cohen and Fabio Gagliardi Cozman and Nicu Sebe and Marcelo Cesar Cirelo and Thomas S. Huang. Semisupervised Learning of Classifiers: Theory, Algorithms, and Their Application to Human-Computer Interaction. IEEE Trans. Pattern Anal. Mach. Intell, 26. 2004.

Grigorios Tsoumakas and Ioannis P. Vlahavas. Effective Stacking of Distributed Classifiers. ECAI. 2002.

Jun Wang and Bin Yu and Les Gasser. Concept Tree Based Clustering Visualization with Shaded Similarity Matrices. ICDM. 2002.

Richard Nock. Inducing Interpretable Voting Classifiers without Trading Accuracy for Simplicity: Theoretical Results, Approximation Algorithms, and Experiments. J. Artif. Intell. Res. JAIR, 17. 2002.

Stephen D. Bay. Multivariate Discretization for Set Mining. Knowl. Inf. Syst, 3. 2001.

Jochen Garcke and Michael Griebel and Michael Thess. Data Mining with Sparse Grids. Computing, 67. 2001.

Haixun Wang and Carlo Zaniolo. CMP: A Fast Decision Tree Classifier Using Multivariate Predictions. ICDE. 2000.

Khaled A. Alsabti and Sanjay Ranka and Vineet Singh. CLOUDS: A Decision Tree Classifier for Large Datasets. KDD. 1998.

Pedro Domingos. Linear-Time Rule Induction. KDD. 1996.

Nir Friedman and MoisÃ©s Goldszmidt. Discretizing Continuous Attributes While Learning Bayesian Networks. ICML. 1996.

Ron Kohavi. Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid. KDD. 1996.

Ron Kohavi. A Study of Cross-Validation and Bootstrap for Accuracy Estimation and Model Selection. IJCAI. 1995.

Ron Kohavi. The Power of Decision Tables. ECML. 1995.

Krzysztof Grabczewski and Wl/odzisl/aw Duch. THE SEPARABILITY OF SPLIT VALUE CRITERION. Department of Computer Methods, Nicolaus Copernicus University.

Mohammed Waleed Kadous and Claude Sammut. The University of New South Wales School of Computer Science and Engineering Temporal Classification: Extending the Classification Paradigm to Multivariate Time Series.

Adil M. Bagirov and Julien Ugon. An algorithm for computation of piecewise linear function separating two sets. CIAO, School of Information Technology and Mathematical Sciences, The University of Ballarat.

Ron Kohavi and George H. John. Automatic Parameter Selection by Minimizing Estimated Error. Computer Science Dept. Stanford University.

Wl odzisl/aw Duch and Rudy Setiono and Jacek M. Zurada. Computational intelligence methods for rule-based data understanding.

Chris Giannella and Bassem Sayrafi. An Information Theoretic Histogram for Single Dimensional Selectivity Estimation. Department of Computer Science, Indiana University Bloomington.

Christophe Giraud and Tony Martinez. ADYNAMIC INCREMENTAL NETWORK THAT LEARNS BY DISCRIMINATION. AA. Wl odzisl and Rafal Adamczak and Krzysztof Grabczewski. Optimization of Logical Rules Derived by Neural Procedures. Department of Computer Methods, Nicholas Copernicus University.

Chih-Wei Hsu and Cheng-Ru Lin. A Comparison of Methods for Multi-class Support Vector Machines. Department of Computer Science and Information Engineering National Taiwan University.

Jeffrey P. Bradford and Clayton Kunz and Ron Kohavi and Clifford Brunk and Carla Brodley. Appears in ECML-98 as a research note Pruning Decision Trees with Misclassification Costs. School of Electrical Engineering.

Jun Wang. Classification Visualization with Shaded Similarity Matrix. Bei Yu Les Gasser Graduate School of Library and Information Science University of Illinois at Urbana-Champaign.
