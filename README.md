**Depression Detection on Social Media**
========================================

This project predicts depression using Reddit comments. By leveraging machine learning, natural language processing (NLP), and embeddings, it identifies depression-related text patterns.

**Features**
------------

-   **Dataset**: eRisk dataset of Reddit comments.
-   **Text Preprocessing**: Cleaning, lemmatization, and tokenization.
-   **Feature Extraction**:
    -   Pre-trained embeddings: Google Word2Vec, Facebook FastText.
    -   Custom-trained embeddings.
-   **Imbalance Handling**: SMOTE for synthetic oversampling.
-   **Model**: Bidirectional LSTM with regularization and dropout.

**Performance**
---------------

| Metric | Value |
| --- | --- |
| Accuracy | 62.44% |
| Precision | 58.73% |
| Recall | 83.98% |
| F1-Score | 69.12% |
| AUC-ROC | 62.42% |
| AUC-PR | 75.36% |

**Installation**
----------------

1.  Clone the repository:

    bash

    Copy code

    `git clone https://github.com/username/repo-name.git`

2.  Navigate to the directory:

    bash

    Copy code

    `cd repo-name`

3.  Install dependencies:

    bash

    Copy code

    `pip install -r requirements.txt`

4.  Download pre-trained models:
    -   GoogleNews Word2Vec
    -   Facebook FastText

**Usage**
---------

1.  **Preprocessing**:

    python

    Copy code

    `python preprocess.py`

2.  **Training**:

    python

    Copy code

    `python train_model.py`

3.  **Evaluation**:

    python

    Copy code

    `python evaluate_model.py`

**Enhancements**
----------------

Future work includes:

-   Incorporating transformer models like BERT.
-   Adding metadata-based features.
-   Improving hyperparameter optimization.

**Contributors**
----------------

-   [Hossein](https://github.com/hossein-glm)

**License**
-----------

This project is licensed under the MIT License.
