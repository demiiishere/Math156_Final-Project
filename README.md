
# Code Repository for MATH 156 Final Project: Future Sales Forecasting with CNN based models

This repository contains code, models, and data for a project focused on time series forecasting and processing using Convolutional Neural Networks (CNN) and modified Temporal Convolutional Networks (TCN).

### Project Structure

Files and Directories

	•	CNN_preprocessing.ipynb: Notebook for preprocessing the data specifically for models.
 
	•	cnn.ipynb: Implementation of the Convolutional Neural Network (CNN) model.
 
	•	cnn_model.pth: Saved model weights for the CNN model.
 
	•	sales_full_bymonth.csv: The dataset used for training and evaluation, containing monthly sales data.
 
	•	tcn.ipynb: Implementation of the Temporal Convolutional Network (TCN) model.
 
	•	tcn_attention.ipynb: Implementation of the enhanced TCN model with attention mechanisms.(Our main contribution)
 
	•	tcn_model.pth: Saved model weights for the TCN model.
 
	•	49_1.png and 49_3.png: Images used for visualization or documentation purposes.
 
	•	.DS_Store: System file (can be ignored or removed).

### Setup and Usage

#### Prerequisites
	•	Python 3.8 or later
	•	Required Python packages: install manually:
 

pip install numpy pandas torch matplotlib jupyter scikit-learn



#### Running the Notebooks
##### 1.	Clone the repository:

	•	git clone <url>


##### 2.	Navigate to the project directory:

  	•	cd code


##### 3.	Start Jupyter Notebook:

  	•	jupyter notebook


##### 4.	Open and run any .ipynb files in the order:
   
	•	CNN_processing.ipynb (data preparation)
	•	cnn.ipynb.ipynb or tcn.ipynb or tcn_attention.ipynb (model-specific data prep and training)

### Results
	•	The saved model files (cnn_model.pth and tcn_model.pth) represent trained models.
	•	Visualizations are included in the notebooks.

### Contribution

Feel free to fork this repository and submit pull requests for improvements.
