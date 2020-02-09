
# Auteur
  ### AMON Sablin
  M2 CHPS - Université Paris Saclay (UVSQ)

# EDP TP2
Évaluation de performance

## Sujet
Le sujet se trouve à la racine de ce dossier appelé "TP_Evaluation_de_performances_2.pdf"

## Description
Le but ici est crée un outil de post-traitement qui va exploité l'outil FIO.

### Outils

- Langage : python
  - matplotlib : pour generer les graphiques
  - os :  pour executer les commandes systèmes
  intaller matplotlib au cas ou vous ne l'avez pas
 ```bash
pip3 install matplotlib
```
- FIO: nous permet d'écrire des programmes pour des cas de test spéciaux pour tester une charge de travail spécifique, soit pour des raisons de performances, soit pour trouver / reproduire un beugs.
```bash
sudo apt install fio
```
ou
```bash
sudo apt-get install fio
```
## Executer

Vous pouvez lancer execution du code comme ceci 
```bash
python3 traitement.py
```
il y a un traitement (donc une fonction traitement) en fonction de chaque question (1, 2 ,3,4)
pour la premiere question pour une ecriture aléatoire il faut:
```python
traitement1("randwrite")
```
pour une ecriture sequentiel:
```python
traitement1("write")
```

pour executer un traitement il faut commenter et decommenter une fonction pour eviter que l'execution soit longue.
exemple:
```python
#traitement1("randwrite")
traitement2()
#traitement3()
```
pour excuter le traitement 2 (question 2)

## Les fonctions

- graphique() : Faire un plot des resultats
- my_range(): generer de start a step par pas de step
- my_range2(): generer des puissance de 2
- file(): permet de creer et configurer le fichier .fio
- file1(): fait la même chose que file mais permet de definir bssplit
- traitement1(): question 1
- traitement1(): question 2
- traitement1(): question 3
- traitement1(): question 4


## License
[MIT](https://choosealicense.com/licenses/mit/)
