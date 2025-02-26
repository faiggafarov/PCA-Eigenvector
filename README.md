# PCA Using Eigenvectors

## Overview
This project demonstrates **Principal Component Analysis (PCA)** using **Eigenvalues and Eigenvectors** on the famous **Iris dataset**. PCA is a dimensionality reduction technique used in data analysis and machine learning to extract the most significant features from high-dimensional datasets.

## Features
- Data preprocessing (handling missing values, standardization)
- Scatter plot visualization of the dataset
- Covariance matrix computation
- Eigen decomposition (Eigenvalues and Eigenvectors)
- Selecting principal components based on variance explained
- Data projection onto a lower-dimensional space
- Final visualization of transformed data

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
The **Iris dataset** consists of 150 samples of iris flowers, categorized into three species:
- **Iris-setosa**
- **Iris-versicolor**
- **Iris-virginica**

Each sample has four features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

## Installation & Usage
### Prerequisites
Ensure you have Python installed along with the required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Running the Code
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/pca-using-eigenvectors.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pca-using-eigenvectors
   ```
3. Run the Jupyter Notebook or execute the Python script:
   ```bash
   jupyter notebook pca_using_eigenvector.ipynb
   ```
   or
   ```bash
   python pca_using_eigenvector.py
   ```

## Key Steps in PCA Implementation
1. **Data Standardization:**
   - Ensures all features have a mean of 0 and variance of 1.
2. **Compute Covariance Matrix:**
   - Measures relationships between features.
3. **Eigen Decomposition:**
   - Compute **Eigenvalues** and **Eigenvectors**.
4. **Select Principal Components:**
   - Choose the top k components based on explained variance.
5. **Transform Data to Lower-Dimensional Space:**
   - Project the original dataset onto the new feature space.
6. **Visualization of Principal Components:**
   - Scatter plot of transformed data in 2D space.

## Results
- The first two principal components capture more than **95%** of the total variance.
- The transformed dataset is visualized in a **2D scatter plot**, clearly distinguishing between the three iris species.


### Explained Variance
```
1. Variance Explained: [72.9%, 22.8%, 3.1%, 1.2%]
2. Cumulative Variance Explained: [72.9%, 95.7%, 98.8%, 100%]
```



## Contributing
Contributions are welcome! If you find any issues or have suggestions, feel free to open a pull request.

## Author
Faig Gafarov - [GitHub Profile](https://github.com/faiggafarov)
