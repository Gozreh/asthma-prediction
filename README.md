# Asthma-prediction
Masters project on the early prediction of asthma exacerbations.

The Jupyter Notebook runs from top to bottom in one go, but requires the user to have access to the Daily Prompt Survey dataset found here: https://www.synapse.org/#!Synapse:syn8361748/tables/

The data used comes from the Asthma Mobile Health Survey. The Daily Prompt Survey saw participants being asked 8 questions about their asthma each day. The goal was to use the data from one week to predict whether a participant's asthma will decline in the following week (on a per patient basis).

The data is grouped by patient into windows of size seven days to extract labels and features. Five different models are then tested to predict whether a patient will experience an asthma exacerbation in the next week.

Since the dataset in question is medically sensitive, output cells from the notebook have been cleared.
