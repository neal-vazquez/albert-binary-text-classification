# ALBERT Binary Text Classification for Movie Reviews

## Overview
This Python script is designed to perform binary text classification using the ALBERT model. The original scope was to categorize movie reviews as either positive or negative based on the text content. Dataset is the [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) originally found on Kaggle.

## Libraries Used
### Data Manipulation and Calculation
1. **Pandas**: For loading and preprocessing the dataset
2. **NumPy**: For numerical computations

### Visualization
1. **Matplotlib**: For basic data visualization
2. **Seaborn**: For additional visualization features

### Deep Learning
1. **PyTorch**: For tensor computations and building the ALBERT model
    - **torch.nn**: For constructing layers of the neural network
3. **Transformers**: For importing the ALBERT model architecture and tokenizer
4. **Scikit-learn (sklearn)**: For model evaluation metrics


## Script Structure
1. **Import Libraries**: Import all the necessary Python libraries.
2. **Data Loading and Preprocessing**: Load and preprocess the movie reviews dataset.
3. **Model Architecture**: Set up the ALBERT model for text classification.
4. **Training and Evaluation**: Train the model on the dataset and evaluate its performance.

## How to Run
1. Ensure all the required libraries are installed.
2. Place the dataset in the correct directory.
3. Run the script.

## Author
Neal Vazquez

## License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
