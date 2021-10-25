# BIRCH algorithm implementation from scratch

- The data files for benchmark artificial dataset which contains datasets of birch, cure , disk , donut , and square, can be found in the "data" folder and are labelled accordingly. They all are in " .arff " format.

- The code which comprehensively contains implementation of BIRCH algorithm from scratch and its integration with preprocessed data can be found in the "code" folder. In that folder, " BIRCH_algo.ipynb " is the file which must be run to run the project end to end. The path is already set to the data folder in an os independent manner and requires no path changes. By default the code contains path to square dataset's 1st file - "square1.arff". You can change the files of the dataset (as per the desired dataset you wish to be fed to BIRCH algorithm) in the penultimate cell of this jupyter notebook file.

- The results both before and after application of the algorithm on each dataset file are captured and saved in the "plots" folder. This folder contains 2 sub folders. One of those named "plots_before_Birch" contains the plots of data just as is imported from the dataset folder whereas the other folder named "plots_after_Birch" contains the plots after application of the algorithm on the dataset. The naming of these plot files is done in such a way that it is very convenient to match its corresponding dataset file from the "data" folder. For example if "square1.arff" from "data" folder is fed to the algorithm, then its corresponding plots are named as "square1_before.png" in "plots_before_Birch" folder and "square1_after.png" in "plots_after_Birch" folder.

- Go through the report and slides present in the "report" folder for more detailed explanations of algorithm and its implementation.
