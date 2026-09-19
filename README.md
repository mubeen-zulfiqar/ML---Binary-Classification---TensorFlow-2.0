# ML---Binary-Classification---TensorFlow-2.0

Historical machine learning project from January 2024, exploring binary classification with TensorFlow/Keras and scikit-learn's built-in breast-cancer dataset.

## Notebook contents

`Binary_Classification.ipynb` loads the dataset, creates a train/test split, standardizes features using the training data, trains a classifier, and plots training and validation loss.

## Evaluation context

The notebook passes its test split to training as validation data. It therefore does not provide a separate, untouched final test set. The data split is also not seeded. This is a learning exercise rather than a validated clinical application.

## Environment

The notebook imports TensorFlow, scikit-learn, and Matplotlib. Dependency versions are not pinned; the repository name reflects the original project title rather than a currently verified compatibility guarantee. The original code is preserved, and execution has not been revalidated as part of this documentation update.
