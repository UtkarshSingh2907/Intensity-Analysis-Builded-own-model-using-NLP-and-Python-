{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "f3c1c9ed-ab77-47dd-a35b-ebb902b48d55",
   "metadata": {},
   "source": [
    "# Intensity Analysis"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "cc9621e4-caed-4e90-8d8a-e40c7df7b155",
   "metadata": {},
   "source": [
    "## Project Overview\n",
    "\n",
    "The \"Intensity Analysis\" project aims to analyze and predict emotions in text, such as happiness, sadness, or anger. With the rise of online reviews and social media, it's important for businesses to understand how people feel in their messages.\n",
    "\n",
    "This project develops a system that uses Natural Language Processing (NLP) and machine learning models, specifically Support Vector Machines (SVM) or a Voting Classifier, to identify emotions and their intensity in text."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "bc3ebb99-722f-422e-a3ef-111f74000bee",
   "metadata": {},
   "source": [
    "## Project Steps\n",
    "\n",
    "1. **Data Cleaning**: The text data is cleaned to remove special characters and make all text lowercase.\n",
    "2. **Feature Extraction**: Features are extracted from the text using TF-IDF vectorization.\n",
    "3. **Model Selection and Training**:\n",
    "    - **Support Vector Machine (SVM)**: Trained and evaluated to classify emotions in the text.\n",
    "    - **Voting Classifier**: An ensemble model combining multiple classifiers to enhance prediction accuracy.\n",
    "4. **Performance Evaluation**: Both models were evaluated based on accuracy and other performance metrics."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "2f59a5c3-aca8-4daa-b4b6-8cb90c05a218",
   "metadata": {},
   "source": [
    "## Models\n",
    "\n",
    "- **Support Vector Machine (SVM)**: Achieved an accuracy of 79.17%.\n",
    "- **Voting Classifier**: Achieved an accuracy of 80.64%."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "32ad7190-c8df-409c-b876-32fefdd6330e",
   "metadata": {},
   "source": [
    "## Requirements\n",
    "\n",
    "- Python 3.x\n",
    "- pandas\n",
    "- scikit-learn\n",
    "- joblib\n",
    "- imbalanced-learn\n",
    "- nltk"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "beaa6260-42eb-4a1d-a0d7-cdf484583fc7",
   "metadata": {},
   "source": [
    "## Installation\n",
    "\n",
    "To install the required packages, use the following command:\n",
    "\n",
    "```bash\n",
    "pip install pandas scikit-learn joblib imbalanced-learn nltk"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "2809fe8c-f738-4e8f-a71d-51996ec89012",
   "metadata": {},
   "source": [
    "### Usage\n",
    "Prepare the Data: Ensure that happiness.csv, angriness.csv, and sadness.csv are in the same directory as the code.\n",
    "Run the Code: Execute the Jupyter notebook or Python script to train the models and evaluate their performance.\n",
    "Model Files: The trained models and vectorizers are saved as .pkl files in the models directory."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "15697644-c818-40ee-bdf4-49dc8c623c58",
   "metadata": {},
   "source": [
    "### Model Files\n",
    "models/svm_model.pkl: Trained Support Vector Machine model.\n",
    "models/voting_model.pkl: Trained Voting Classifier model."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "e8efbf6a-6771-4c98-85e5-edb70a5696cb",
   "metadata": {},
   "source": [
    "### Future Work\n",
    "Experiment with more advanced models and techniques to further improve accuracy.\n",
    "\n",
    "Explore additional features or data sources to enhance the emotional analysis."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "da96cf32-6759-4ff0-b627-79db04644d7e",
   "metadata": {},
   "source": [
    "### Conclusion\n",
    "This project provides a reliable tool for real-time emotional analysis of text, leveraging advanced NLP and machine learning techniques to deliver accurate predictions of emotions."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "45171970-f410-4a9b-8253-f431c4c61c1a",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.11.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
