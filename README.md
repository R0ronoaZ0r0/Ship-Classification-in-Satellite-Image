# Ship Classification in Satellite Imagery

This project implements a custom Convolutional Neural Network (CNN) optimized using a Genetic Algorithm (GA) for clustering and classification tasks.

## Prerequisites

- **Python 3.x**
- **Jupyter Notebook**
- **Libraries**: `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `tensorflow` or `keras` (and other dependencies used in the notebooks).

## Setup

Before running any of the notebooks, you must update the file paths to match your local environment.

1.  Open each `.ipynb` file.
2.  Locate the base file path variable at the top of the file.
3.  Change it to the directory where you have stored the project files.

## Usage

Follow these steps in order to run the project:

### 1. Data Preparation
Run the **`load_data.ipynb`** notebook.
-   **Purpose**: This script loads the raw data and creates the dataset required for the subsequent steps.

### 2. Feature Extraction & Clustering
Run the **`clustering.ipynb`** notebook.
-   **Purpose**: This script extracts features from the data and performs clustering.

### 3. Model Training & Testing
Run the **`model_training.ipynb`** notebook.
-   **Purpose**: This script trains and tests the dataset using the clusters generated in the previous step.
-   **Note**: You can manually adjust the model architecture in this file if needed.

## Optimization (Optional)

If you wish to re-optimize the model architecture:

1.  Run the **`genetic.ipynb`** notebook.
    -   **Purpose**: This script uses a Genetic Algorithm to find the optimal architecture for the given clustering.
2.  Update the architecture in `model_training.ipynb` based on the results from the genetic algorithm.

## Project Structure

-   **`load_data.ipynb`**: Data loading and preprocessing.
-   **`clustering.ipynb`**: Feature extraction and clustering logic.
-   **`model_training.ipynb`**: CNN model training and evaluation.
-   **`genetic.ipynb`**: Genetic Algorithm for hyperparameter/architecture optimization.
-   **`README.md`**: Project documentation.
