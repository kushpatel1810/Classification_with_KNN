# Classification_with_KNN
This is a part of my assignment in the course, ECE 657A Data and Knowledge - Modeling and Analysis, affiliated with the University of Waterloo. Here, abalone fish dataset is analysed and KNN classification is used to predict the age.

Primarily, the dataset is assessed to check the distribution of the data within the dataset. The summarization statistics were used on the data features and important features were highlighted and taken into account.

Firstly, the normal train-test model was implemented and the accuracy was obtained.  After that, for the same divided data, KNN was inplemented using 5-fold CV for k value ranging from 1 to 200 and the accuracy was calculated.

Afterwards, weights were being assigned to the neighbors, both uniform and distance weights were implemented to obtain accuracy.

Finally, a comparison graph was plotted for different weighted accuracies to be compared and get the most apt one.
