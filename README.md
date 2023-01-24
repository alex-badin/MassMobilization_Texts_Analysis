# MassMobilization_Texts_Analysis
Analysis of news on protests, including topic modelling and classification on whether protests were violent or not.

Analysing protest data from Mass Mobilization Protest Data. Specifically, analysis of notes variable (news texts) on protests, including classification on whether protests were violent or not; the class variable (violent / non-violent) is present in the database.

The notebook includes:

- top-level analysis of database
- LDA (Latent Dirichlet Allocation) for topic modeling - understanding themes the news on protets cover
    - on word counts & TF-IDF
- NMF (Non-negative Matrix Factorization) - for the same purpose
  - on TF-IDF
- Classification of notes - whether protest was violent or not
  - simple log regression (on tf-idf data)
  - log regression based on LSA (Latent Semantic Analysis)
  - Additionally, semantic analysis in 2 dimensional space
  - Analysis of number of dimensions and model accuracy

The database can be accessed via web page: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HTTWYL
