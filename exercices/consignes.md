# Exos

## Exercice 1 : Créer un projet

1. Connectez-vous à Squash TM.

2. Créez un nouveau projet appelé "Projet Testeurs".

3. Ajoutez une description au projet pour expliquer brièvement son objectif.

## Exercice 2 : Définir les exigences

1. Dans le projet "Projet Testeurs", créez une nouvelle exigence intitulée "Connexion utilisateur".

2. Ajoutez les critères suivants à l'exigence :
    - L'utilisateur doit pouvoir se connecter avec un nom d'utilisateur et un mot de passe valides.
    - L'utilisateur doit recevoir un message d'erreur s'il entre des informations incorrectes.

## Exercice 3 : Créer des cas de test

1. Créez un nouveau cas de test intitulé "Test de connexion réussie".

2. Définissez les étapes suivantes pour le cas de test :
    - Ouvrir la page de connexion.
    - Entrer un nom d'utilisateur valide.
    - Entrer un mot de passe valide.
    - Cliquer sur le bouton de connexion.
    - Vérifier que l'utilisateur est redirigé vers la page d'accueil.

3. Créez un autre cas de test intitulé "Test de connexion échouée".
    - Suivez des étapes similaires mais avec des informations incorrectes et vérifiez la réception du message d'erreur.

## Exercice 4 : Lier les exigences aux cas de test

1. Liez l'exigence "Connexion utilisateur" aux deux cas de test créés dans l'exercice précédent.

## Exercice 5 : Créer une campagne de test

1. Créez une nouvelle campagne de test intitulée "Campagne de test de connexion".

2. Ajoutez les cas de test "Test de connexion réussie" et "Test de connexion échouée" à cette campagne.

## Exercice 6 : Exécuter les tests

1. Exécutez la campagne de test "Campagne de test de connexion".

2. Pour chaque cas de test, indiquez si le test a réussi ou échoué.
    - Pour le "Test de connexion réussie", marquez le test comme réussi.
    - Pour le "Test de connexion échouée", marquez le test comme échoué et ajoutez un commentaire expliquant le problème.

## Exercice 7 : Gérer les anomalies

1. Pour le cas de test échoué, créez une anomalie intitulée "Problème de connexion".

2. Associez cette anomalie au cas de test "Test de connexion échouée".

## Exercice 8 : Rapports

1. Générez un rapport de test pour la campagne "Campagne de test de connexion".

2. Incluez dans le rapport les résultats des tests et les anomalies associées.

## Exercice 9 : Utiliser les configurations de test

1. Créez une configuration de test intitulée "Configuration navigateur Chrome".

2. Ré-associez les cas de test de la campagne "Campagne de test de connexion" à cette configuration.

## Exercice 10 : Paramétrer les jeux de données

1. Créez un jeu de données pour le cas de test "Test de connexion réussie" contenant différentes paires nom d'utilisateur/mot de passe.

2. Configurez le cas de test pour utiliser ce jeu de données pendant l'exécution de la campagne.
