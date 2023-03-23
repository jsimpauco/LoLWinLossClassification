# LoLWinLossClassification
Project for DSC80 at UCSD

*An exploratory analysis of the dataset can be accessed [here](https://jsimpauco.github.io/LoLSupportsVsJunglers/)*

# Problem Identification

With the dataset containing statistics from professional League of Legends games played in 2022, the following question is proposed: Given a team’s stats after a single competitive game, can we predict if the team won (or lost) the match? This type of prediction problem is a binary classification problem with the outcomes being a win (represented as 1 in the dataset) or a loss (0 otherwise). The ‘result’ is the response variable in this proposal. It was chosen because players care the most about winning/losing a game, and thus was a higher priority to predict. The metric that will be used to evaluate the model will be accuracy score. Accuracy was chosen over F1-score since there are no class imbalances and both false positives and false negatives are equally bad for the model. The features used will be statistics that will be known at the end of the game, meaning that the time of prediction will allow for most of the data to be used.