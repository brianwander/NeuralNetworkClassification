# Neural Network Classification
This notebook uses a neural network that trains on data from startup applications to predict whether or not a startup will be successful. The model is then optimized by varying the number of neurons in hopes of obtaining higher accuracy metrics.

## Technologies
This notebook runs on a jupyter notebook.
The program uses the pandas, tensorflow, and sklearn libraries.

## Installation Guide
Install python 3.7.15 and open venture_funding_with_deep_learning.ipynb using jupyter lab, ensuring that the applicants_data.csv file containing the data is in the Resources folder.

To install the latest version of sklearn use the following command:

pip install -U scikit-learn

To install the latest version of tensorflow use the following command:

pip install tensorflow

Pandas can be installed by downloading the Anaconda python distribution and following the installation instructions.

## Usage
The code runs directly in the jupyter notebook. Data is first read from the csv file, then encoded into numerical values and scaled. The data is split between training and testing, and the neural network is built on the training data. Additional neurons or layers can be added by modifying the code, and metrics will be displayed after the model has been created.

## Contributors

By Brian Wander
brianwander101@gmail.com
www.linkedin.com/in/brian-wander

---

## License

Free to use with proper attribution.
