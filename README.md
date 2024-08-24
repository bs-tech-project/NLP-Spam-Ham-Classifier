# Spam Vs Ham Classification [SMS] README

## Overview

The Spam Vs Ham Collection [SMS] dataset consists of 5,574 SMS messages, each labeled as either "ham" (legitimate) or "spam". This dataset is used for the purpose of training and evaluating models that can classify SMS messages as spam or ham. 

## Dataset Description

- **Total Messages:** 5,574
  - **Ham (Legitimate):** 4,827 (86.6%)
  - **Spam:** 747 (13.4%)

- **Format:** 
  - Each line contains two columns:
    - **Label:** `ham` or `spam`
    - **Message Text:** The content of the SMS message

- **Examples:**
  - `ham   What you doing?how are you?`
  - `spam   URGENT! Your Mobile No 07808726822 was awarded a L2,000 Bonus Caller Prize on 02/09/03! This is our 2nd attempt to contact YOU! Call 0871-872-9758 BOX95QU`

## Data Sources

1. **Grumbletext Web Site:** 425 SMS spam messages collected manually.
   - [Grumbletext Web Site](http://www.grumbletext.co.uk/)

2. **Caroline Tag's PhD Theses:** 450 SMS ham messages.
   - [PhD Thesis](http://etheses.bham.ac.uk/253/1/Tagg09PhD.pdf)

3. **NUS SMS Corpus:** 3,375 SMS ham messages from Singapore.
   - [NUS SMS Corpus](http://www.comp.nus.edu.sg/~rpnlpir/downloads/corpora/smsCorpus/)

4. **SMS Spam Corpus v.0.1 Big:** 1,002 SMS ham messages and 322 spam messages.
   - [SMS Spam Corpus v.0.1 Big](http://www.esp.uem.es/jmgomez/smsspamcorpus/)

## Jupyter Notebook: `spamVsHamClassification.ipynb`

This notebook outlines the steps to build a classification model for detecting SMS spam messages.

### Steps in the Notebook

1. **Import Libraries:** Import necessary Python libraries for data manipulation, visualization, and machine learning.

2. **Load and Prepare the Dataset:** Load the dataset and prepare it for preprocessing.

3. **Data Preprocessing:** Clean and preprocess the text data, including tokenization and removal of stop words.

4. **Feature Extraction and Model Building:** Convert the text data into numerical features using techniques such as TF-IDF and build a classification model.

5. **Train the Model:** Train the model on the training dataset.

6. **Predictions and Evaluation:** Make predictions on the test dataset and evaluate the model's performance using metrics like accuracy, precision, recall, or F1-score.

7. **Classification Report Visualization:** Visualize the classification report using Seaborn for better interpretability.

## Requirements

To run the Jupyter notebook and execute the classification, ensure you have the following libraries installed:

- `pandas`
- `numpy`
- `scikit-learn`
- `seaborn`
- `nltk` (for natural language processing)

You can install these libraries using pip:

```bash
pip install pandas numpy scikit-learn seaborn nltk
```

## Usage

1. Clone this repository or download the notebook and dataset.
2. Open `spamVsHamClassification.ipynb` in Jupyter Notebook.
3. Follow the steps outlined in the notebook to run the analysis and build the classification model.

## Acknowledgements

- The dataset and sources referenced in this README.
- The contributors and researchers who provided and made this dataset publicly available.
