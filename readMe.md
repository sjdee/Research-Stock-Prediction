# Market Analysis Techniques

This project leverages various machine learning tools to predict the price movement of stocks.

Graph Data can also be found at: https://docs.google.com/spreadsheets/d/1h2iohG01RSHTFPjjJPyFlq6uHYE5OQvl8vNjeOhmg4k

## File Structure

### Extraction

* transform.ipynb
* Sector_Name_Calculation.ipynb

### Classifiers

* RandomForest.ipynb
* KNN.ipynb	
* NaiveBayes.ipynb	
* NeuralNetwork.ipynb	
* DecisionTree.ipynb
* SVM.ipynb	

These files can be configured to operate either on the entire dataset or perform the analysis on various sectors by toggling the following parameters:

* check_each_sector: Perform a sector wise analysis if True
* less_columns: Use only the columns selected after Feature Selection if True
* minify: output only the precsion for buy signals, recall for sell signals and overall accuracy instead of the entire sklearn classification report if True
* print_data: prints the output as the classifier is run if True

### Results
* Graph Data and Graphs.zip	




