# Integrating (Deep) Machine Learning and Cheminformatics for Predicting Human Intestinal Absorption of Small Molecules
# Overview
A set of 2648 compounds were collected from some early as well as recent works and curated to build a robust dataset. Five machine learning (ML) algorithms have been trained with a set of molecular descriptors of these compounds which have been selected after rigorous feature engineering. Additionally, a graph convolution neural network (GCNN) based model was developed using the same set of compounds to exploit the predictability with automated extracted features.  
# Findings
The numerical analyses show that out the five ML models, Random forest and LightGBM could predict with an accuracy of 87.71% and 86.04% on the test set and 95% and 89% with the external validation set respectively. Whereas with the GCNN based model, the final accuracy obtained was 74.58% and 82% on the external test set.
# Dependencies
 Package                   Version
------------------------- --------------
interpret                 0.6.2
ipykernel                 6.29.3
ipython                   8.25.0
jupyter                   1.0.0
lightgbm                  4.4.0
matplotlib                3.9.0
mordred                   1.2.0
notebook                  7.2.0
numba                     0.60.0
numpy                     1.26.4
openpyxl                  3.1.5
pandas                    2.2.2
pip                       24.0
plotly                    5.23.0
rdkit                     2023.9.6
scikit-learn              1.5.1
scipy                     1.14.0
seaborn                   0.13.2
shap                      0.46.0
sklearn-rvm               0.1.1
torch                     2.3.1
torch_geometric           2.5.3
torchaudio                2.3.1
torchvision               0.18.1
wheel                     0.43.0
widgetsnbextension        4.0.11
xgboost                   2.1.0

