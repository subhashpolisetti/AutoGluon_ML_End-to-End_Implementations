
# California House Prices Prediction using AutoGluon

This project demonstrates how to use AutoGluon to predict California house prices. The dataset is sourced from Kaggle, and this guide will walk you through downloading it and setting up your environment.

## Steps to Download California House Prices Dataset from Kaggle

### 1. Set Up Kaggle API
To download the dataset directly from Kaggle, you'll need to set up the Kaggle API. Follow these steps:

1. Go to the Kaggle website and log in to your account.
2. Navigate to your Kaggle account settings by clicking on your profile picture in the top right corner, then selecting **Account**.
3. Scroll down to the **API** section and click on **Create New API Token**.
4. A file named `kaggle.json` will be downloaded. This file contains your API credentials.

### 2. Upload `kaggle.json` to Colab

1. In your Colab environment, upload the `kaggle.json` file by running the following code in a code cell:

   ```python
   from google.colab import files
   files.upload()  # Upload kaggle.json here
