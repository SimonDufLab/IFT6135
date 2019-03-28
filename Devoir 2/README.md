# Devoir 2

models.py contient les réseaux RNN, GRU et le transformer module. Exécutez avec ptb-lm.py et le parser

#####################################################################################################

ptb-lm-5_1.py permet de générer la perte moyenne à chaque séquence (problème 5.1). Exécutez avec le parser (modèles de 4.1) et ajustez le dictionnaire des meilleurs paramètres étant chargé pour correpondre au modèles utilisé. La perte moyenne sera contenue dans la variable : val_loss_time

#####################################################################################################

ptm-lm-5_2RNN/GRU permettent de calculer la moyenne du gradient aux couches cachées pour une mini-batch (problème 5.2). Exécutez avec le parser (modèles de 4.1). Importera les modèles de models_5_2.py. Les gradients seront contenus dans les variables: grad_time (RNN) et grad_time_2 (GRU)

#####################################################################################################

samples.py permet de générer des échantillons (problème 5.3). Exécutez avec le parser (modèles de 4.1) et ajustez le dictionnaire des meilleurs paramètres étant chargé pour correpondre au modèles utilisé. Les échantillons seront contenus dans la variable : samples
