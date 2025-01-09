This directory contains the four Jupyter notebooks used in the final project for the SSY316 course. Below is a brief summary of each notebook. 

## Usage

The usage is very straight forward, the datasets and the requirements.txt are provided. Run this in a virtual environment. 

### P1.ipynb 

**Topic:** Clustering with Gaussian Mixture Models, K-Means, Gibbs Sampling, and Metropolis-Hastings. 

- **Synthetic GMM Data Generation**: A function that generates data from a predefined Gaussian Mixture Model (10 components). 
- **K-Means Implementation**: A custom K-Means algorithm to cluster the synthetic data. 
- **Gibbs Sampling**: Demonstrates how to cluster data using a simple Gibbs sampler. 
- **Metropolis-Hastings**: Shows multiple runs with varying proposal variances, comparing the ARI (Adjusted Rand Index) scores. 
- **Performance Comparison**: Uses metrics like execution time and ARI to compare different clustering methods. 

--- 

### P2.ipynb 

**Topic:** Classification on MNIST data using Naive Bayes and Logistic Regression. 

- **Data Loading**: Fetches the MNIST dataset from OpenML. 
- **Data Binarization**: Converts pixel intensities to binary form for simpler demonstration. 
- **Naive Bayes Classifier**: Implements Laplace smoothing and probability calculations 
- **Logistic Regression**: Uses scikit-learn’s multinomial logistic regression. 
- **Comparison**: Evaluates both methods on accuracy, timing, and class-wise performance. 

--- 

### P3.ipynb 

**Topic:** Bayesian Skill Rating and TrueSkill-like updates with an ADF (Assumed Density Filtering) approach. 

- Demonstrates skill rating updates using Gibbs Sampling for simple 2-player models. 
- Uses ADF updates (similar to TrueSkill) for multi-team data. 
- Explores Gaussian posterior computations and truncated normal distributions. 

--- 

### P4.ipynb 

**Topic:** Physics-Based Simulation and Optimization for [QWOP](https://www.foddy.net/Athletics.html) (MCMC, Gradient-based, and Evolutionary Algorithms). 

- **Objective**: Maximize forward movement (distance traveled by the head). 
- **MCMC Optimization**: Randomly perturb the “plan” (control parameters) and accept better solutions. 
- **Gradient-Based Optimization**: Uses finite-differences to approximate gradients on the “plan”. 
- **Evolutionary Algorithm**: Uses selection, crossover, and mutation to evolve a population of plans. 
