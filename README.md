#  Composer Classification
This project uses an LSTM neural network and CNN to classify composers based on MIDI file features.

## Dataset
The dataset consists of MIDI files from 11 different composers. The MIDI files are loaded and features are extracted from each file.

## Feature Extraction
The following features are extracted from the MIDI files:
- Number of instruments
- List of instruments
- Number of programs
- Tempo
- Resolution
- Time signature ratio
- Duration
- Average pitch

## Feature Visualization
The features are visualized to show the distribution of each feature by composer.

## Outlier Removal
Outliers are removed from the dataset using z-scores and IQR methods.

## Correlation Matrix
The correlation matrix is calculated to show the relationships between features.

## Model Training
An LSTM neural network is trained on the dataset to classify composers based on the extracted features.

## Model Evaluation
The model is evaluated on the test set using a confusion matrix and classification report.

## Model Accuracy
The model accuracy is plotted over the number of epochs to show the training progress.

## Model Loss
The model loss is plotted over the number of epochs to show the training progress.

## Requirements
The following libraries are required to run the code:
- pretty_midi
- numpy
- tensorflow
- sklearn
- matplotlib
- seaborn
- pandas

