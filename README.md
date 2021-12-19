# venture-capital-dnn

The purpose of this project is to employ machine learning and deep neural network techniques to analyze and predict whether a startup applicant for a hypothetical venture capital firm will become a successful business. The project uses the provided dataset to create a binary clasifier model. The original model uses a neural network with 2 hidden layers and 100 epochs. At the end of the notebook, two alternative models are provided, with the adjustment of using an additional hidden layer in the first alternative (nn_A1), and using 100 epochs in the second alternative (nn_A2). The results of the alternative models shows that there is not much difference in loss and accuracy of the three neural network models with the use of an additional layer or double the epochs.

## Technologies

This project leverages Python 3.7 with the following libraries: Pandas, pathlib, tensorflow, sklearn

## Installation

Before running the notebook, ensure that you have the latest tensorflow and sklearn installed.

To upgrade tensorflow, run the following code:

```
pip install --upgrade tensorflow
```

Scikit-learn should already be installed with Anaconda, but if it is not installed, run the following code to install the package:

```
pip install -U scikit-learn
```


## Usage

In order to use this project, simply clone the repo and run the notebook to review the analysis.


## Contributors

Brought to you by Austin Do. Email: austindotech@gmail.com

## License
MIT