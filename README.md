# Inferring-Human-Routines-from-Sensor-Data
This is my practice in the clustering method. 
This project is to reproduce the result from the paper:  
Nonparametric Discovery of Human Routines from Sensor Data.  
http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.681.3152&rep=rep1&type=pdf  
This work introduces a approach to model and recognize daily routines such as office work, dinner activities,commuting, lunch routine from wearable sensors. These kinds of high-level routine can be treated as the composition of multiple low-level activities, such as driving bike, driving cart through supermarket, sitting  desk activities, walking while carrying something...etc. These low-level activities can be represented by some features of digital data from sensors.

## Required library  
numpy, matplotlib, pandas, scikit-learn, tomotopy  

## Dataset  
Discovery of Activity Patterns using Topic Models Tam Huynh, Mario Fritz and Bernt Schiele. In Ubicomp'08  
http://datasets.d2.mpi-inf.mpg.de/ubicomp08/dataset_huynh_ubicomp08.zip  

## Models
### Dirichlet process Gaussian mixture model (DPGMM)
### hierarchical Dirichlet process (HDP)
### Affinity Propagation (AP)

## Reference
1. Nonparametric Discovery of Human Routines from Sensor Data,  
Feng-Tso Sun, Yi-Ting Yeh, Heng-Tze Cheng, Cynthia Kuo, Martin Griss  
http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.681.3152&rep=rep1&type=pdf  
2. Discovery of Activity Patterns using Topic Models,
Taˆm Huy`nh, Mario Fritz and Bernt Schiele
http://mobvis.org/publications/ubicomp2008.pdf  
