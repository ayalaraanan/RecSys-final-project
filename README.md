# Reccomendation Systems Final Project
### Applying the two-stage YouTube recommendation system to MovieLens 1M

This project is composed of:

A. The main YouTube model, which includes the following notebooks:
1. [Datasets generation for the candidates model](https://github.com/ayalaraanan/RecSys-final-project/blob/main/1_RecSys_final_project_data_generation_for_candidate_model.ipynb)
2. Candidates model
3. Datasets generation for the ranking model (using the candidates model output)
4. Ranking model

B. A matrix factorization model, which runs with the same model

C. Suggested improvements including:
1. Integrating RNN units for handling viewing history
2. Adding transition information to anticipate the next movie genre

Further details can be found inside the notebooks and in the final report.

## running the notebooks
There are two ways to use the notebooks:

i. If you wish to modify and run all notebooks yourself, you will need to store the outputs for later use by the other notebooks.
I used google drive for the task.

ii. All of my data files, intermediate results, and results are accessible with gdown. You may need to import and run gdown upgrade (which in Google Colab requires restaring the runtime after first installation).
