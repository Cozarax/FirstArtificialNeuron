# FirstArtificialNeuron
 Documentation du Neurone Artificiel pour la Classification Binaire Linéaire
Ce projet implémente un neurone artificiel pour la classification binaire linéaire. Bien que l'exemple principal concerne la classification de plantes comme toxiques ou non toxiques basée sur la largeur et la longueur de leurs feuilles, ce modèle est suffisamment général pour être adapté à d'autres applications de classification binaire linéaire.

Contenu
Génération du Dataset
Visualisation des Données
Initialisation des Paramètres du Modèle
Construction du Modèle de Neurone
Fonction de Coût
Calcul des Gradients
Mise à Jour des Paramètres
Prédiction
Entraînement et Évaluation
Visualisation de la Frontière de Décision
Adaptabilité du Modèle
1. Génération du Dataset
Utilisation de make_blobs de sklearn pour créer un jeu de données simulé. Dans l'exemple fourni, 100 instances représentent les caractéristiques des plantes.

2. Visualisation des Données
Utilisation de Matplotlib pour visualiser le jeu de données, aidant à comprendre la répartition et la séparabilité des classes.

3. Initialisation des Paramètres du Modèle
La fonction initialisation crée des valeurs initiales aléatoires pour les poids W et le biais b.

4. Construction du Modèle de Neurone
La fonction model applique une combinaison linéaire des entrées, suivie d'une fonction d'activation sigmoïde pour la classification binaire.

5. Fonction de Coût
La fonction log_loss mesure la différence entre les prédictions du modèle et les valeurs réelles.

6. Calcul des Gradients
La fonction gradients trouve la dérivée de la fonction de coût par rapport à W et b.

7. Mise à Jour des Paramètres
La fonction update ajuste W et b en utilisant les gradients et un taux d'apprentissage.

8. Prédiction
La fonction predict utilise le modèle entraîné pour classer de nouvelles données.

9. Entraînement et Évaluation
La fonction artificial_neuron entraîne le modèle en répétant la mise à jour des paramètres et calcule la perte à chaque itération. La performance est évaluée avec l'accuracy_score.

10. Visualisation de la Frontière de Décision
Visualisation de la manière dont le modèle distingue les deux classes.

11. Adaptabilité du Modèle
Ce modèle peut être facilement adapté à d'autres problèmes de classification binaire linéaire. En changeant le jeu de données et en effectuant de légers ajustements si nécessaire, le neurone artificiel peut être appliqué à diverses situations où la tâche est de classer des instances en deux catégories distinctes sur la base de leurs caractéristiques.

