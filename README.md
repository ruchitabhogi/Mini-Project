
# Sequential Recommendation System

## Overview
This project implements a Sequential Recommendation System using a dataset of books and user preferences. The goal is to predict and recommend books to users based on their historical interactions and sequences.

The project leverages a dataset containing user-item interactions and builds a machine learning model to provide personalized recommendations in a sequential manner.

## Project Features
- Data Preprocessing: Efficiently handles and processes the dataset for building recommendations.
- Model Training: Trains a model using sequential data to recommend items.
- Recommendation Generation: Generates a list of recommended items for users based on their previous interactions.

## Dataset
The dataset used for this project is stored in the `/content` directory and contains the following files:
- `/content/amazon.csv`  
- `/content/datasets/books/seq`

## Project Structure
```
/content
│
├── amazon.csv  # Main dataset file
├── datasets
│   └── books
│       └── seq # Sequence data for book recommendations
│
└── Sequential Recommendation.ipynb # Main file to run the recommendation system
```

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/ruchitabhogi/Mini-Project.git
   ```

2. Upload the dataset files to the appropriate directories:
   - `/content/amazon.csv`
   - `/content/datasets/books/seq`

3. Navigate to the project directory:
   ```bash
   cd /Mini-Project
   ```

4. Open Sequential Recommendation.ipynb in the Jupyter interface.

5. Run the notebook cells in sequence to preprocess the data, train the model, and generate recommendations.

## Results
Once the code is executed, the model will provide a list of recommended books for each user in the dataset.
https://github.com/user-attachments/assets/8d58f0ca-80cc-4488-a153-5ea2d65810e3
