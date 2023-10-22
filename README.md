# NLP-based-Recommendation-System

This project involves the development of a medicine recommendation system based on user-provided medical conditions or preferences. The recommendation system uses natural language processing (NLP) techniques to match user input with medicines from a dataset. The goal is to provide users with a list of relevant medicines.

## Dataset

The dataset used for this project contains information about various medicines. It includes the following columns:

- `Medicine Name`: The name of the medicine.
- `Composition`: The composition of the medicine.
- `Uses`: The medical conditions or purposes for which the medicine is prescribed.
- `Side_effects`: Possible side effects associated with the medicine.
- `Manufacturer`: The company that manufactures the medicine.
- `Excellent Review %`: The percentage of excellent reviews for the medicine.
- `Average Review %`: The percentage of average reviews for the medicine.
- `Poor Review %`: The percentage of poor reviews for the medicine.

### Data Preprocessing
- Text data in the `Medicine Name`, `Uses`, and `Side_effects` columns is preprocessed using the following steps:
  - Lowercasing
  - Tokenization
  - Removing punctuation and non-alphanumeric characters
  - Removing stopwords
 
## Recommendation System

### Feature Extraction
TF-IDF (Term Frequency-Inverse Document Frequency) vectorization is used to convert the text data into numerical feature vectors.

### User Profile
- Users can provide their medical conditions or preferences as input.

