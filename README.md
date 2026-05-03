# movie-rec-syst
Movie Recommendation System

By: Angelique Garced

Install -
1. Clone the repository
git clone <your-repo-url>
cd movie-rec-syst
2. Install required libraries
pip install pandas numpy matplotlib scikit-surprise

Run the two notebooks (analysis and models) to get statisical info and model results.

Result Summary - 

| Model                      | Performance                                             |
| -------------------------- | ------------------------------------------------------- |
| Global Average             | Worst baseline (ignores personalization)                |
| User-Based CF              | Improved accuracy using similar users                   |
| Item-Based CF              | Slightly better stability than user-based CF            |
| SVD (Matrix Factorization) | Best overall performance due to latent feature learning |
