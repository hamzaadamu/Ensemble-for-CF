# An Ensemble-Based Hybrid Framework for Collaborative Filtering: Combining SVD, Co-Clustering, SlopeOne and NormalPredictor with Meta-Learning Through Linear Regression

This project introduces an ensemble-based hybrid recommender system that integrates multiple CF models using a meta-learning approach via linear regression. By leveraging the strengths of individual algorithms and learning optimal weights for their predictions, our framework delivers improved accuracy and robustness across diverse datasets.

We evaluated the system on three benchmark datasets—MovieLens 1M, Jester Ratings, and Netflix Movie Ratings. The results show that our hybrid model consistently outperforms standalone CF methods in both prediction accuracy and stability, demonstrating the potential of ensemble techniques to enhance real-world recommender.

## Getting Started

This project was developed in **Google Colab** using **Python**. You can run or copy the notebook using the link below:

[Open in Colab](https://colab.research.google.com/drive/12zVSPKZg_O4coMTQW9UgEGTRkY8aa2gf#scrollTo=0X_vLn8IqPH3)

### Requirements

### Although the code runs in Colab (which includes most dependencies), but you have to install surprise depency usin pip install and downgrade colab's numpy2 to numpy1 using pip also:

pip install surprise
pip install "numpy<2"
