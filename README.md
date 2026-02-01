# SDD-distillation-de-model
Repo contenant le code relevant du devoir de SDD,sur l'apprentissage par renforcement. Ce projet illustre de l'article "Distilling the Knowledge in a Neural Network" de Geoffrey Hinton, Oriol Vinyals et Jeff Dean.

## Illustration.py :
NoteBook contenant tout le code executable du projet.

## training_logs/ :
Dossier contenant les sauvegardes au format .npy de tableaux NumPy servant à enregistrer les données d'entraînement.

## trained_model/ :
Dossier contenant les poids des models entraîné. Peuvent être chargés en executant le notebook afin
d’éviter de relancer les entraînements.

## presentation/ :
Dossier contenant le pdf de la presentation ainsi que les images l'illustrant.

## MINST_tests/ :
NoteBook contenant les premiers tests de distillation réalisés sur le dataset MINST. abandoné car ce set est trop simple pour pouvoir illustrer l'article. 