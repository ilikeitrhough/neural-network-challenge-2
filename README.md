# Neural Network Challenge 2

The neural network uses various employee attributes to make predictions.

## Table of Contents

- [Project Overview](#project-overview)
- [Files](#files)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

- **Predict Employee Attrition**: Determine the likelihood of employees leaving the company.
- **Predict Suitable Department**: Identify which department an employee is best suited for.
- **Branched Neural Network**: Utilize a neural network with shared layers and two output branches for dual predictions.

## Files

- `attrition.ipynb`: Jupyter Notebook containing the code for data preprocessing, model creation, training, and evaluation.
- `attrition.csv`: Dataset used for training and testing the neural network (loaded directly within the notebook).

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or Google Colab
- Required Python libraries:
  - pandas
  - numpy
  - scikit-learn
  - TensorFlow (Keras)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/ilikeitrhough/neural-network-challenge-2.git
   ```

2. **Install Dependencies**

   Navigate to the project directory and install the required Python packages:

   ```bash
   pip install pandas numpy scikit-learn tensorflow
   ```

## Usage

1. **Open the Jupyter Notebook**

   - **Option 1: Jupyter Notebook**

     Open a terminal in the project directory and run:

     ```bash
     jupyter notebook attrition.ipynb
     ```

   - **Option 2: Google Colab**

     - Upload `attrition.ipynb` to your Google Drive.
     - Open it with Google Colab for an interactive environment without local setup.

2. **Run the Notebook**

   - Execute each cell sequentially.
   - The notebook includes detailed comments and explanations for each step.

## Results

- **Department Prediction Accuracy**: 94.56%
- **Attrition Prediction Accuracy**: 94.56%

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- **Course Material**: Guidance and resources provided by the course instructors.
- **Data Source**: The dataset is sourced from the course materials provided in the challenge.
