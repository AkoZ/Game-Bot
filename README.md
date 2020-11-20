# Bot copieur (BoC) d'utilisation
### By Arda Mavi pour game bot

ia qui apprend en regardant ce qu'on fait: scrute et enregistre les touches: 
toute appli est donc utilisable du moment que c'est fermé, ex: retouche photo...(?)
mais pour le jeu .. Dota2 sera pris en test

## En résumé: 
0. installer les modules requirements sous Win10: avec CMD (powershell possible ?)<br>
`pip3 install -r requirements.txt`
1. créer la base avec `python3 create_dataset.py`
2. démarrer le jeu - base créée, puis stopper la création de base avec `Ctrl-C` dans le terminal
3. le jeu est en cours, entrainement: `python3 train.py` 
4. JOUER - Arrêter encore avec ctrl-C ?
5. voir ce qu'elle a appris: `python3 ai.py` : elle joue à votre place (ou n'importe quoi ?) ! 

## comment ça marche ?
- 1: démarrer le programme et jouer pendant un moment.
- 2: Puis redémarrer et regarder l'ia jouer le jeu ...

## Au fond quel est le truc ?
Quand vous démarrez le programme pour entrainement, BoC enregistre les mouvements de souris et de clavier.<br>
Artificial intelligence learn: When I push any button?<br/>
And when you run the program, it plays the game just like you!
Est-ce un réel apprentissage ou l'ia va-t-elle juste faire exactement la même chose ?
du coup employer des touches inutilement et faire partir le jeu en vrille ou soritr et planter l'ordi ???
## it learn with deep learning.<br/>
Deep Learning is a subfield of machine learning with neural networks inspired by the structure of the brains artificial neural networks.

### Important Notes:
- Tested in Python version 3.6.0
- Install necessary modules with `sudo pip3 install -r requirements.txt` command.
## WINDOWS Installation:
- Install Python 3.6.0 : https://www.python.org/downloads/release/python-360/
- Run CMD and Input Command `pip3 install -r requirements.txt`

### Créer une base d'entrainement:
1. Run `python3 create_dataset.py` command in terminal.
2. jouer le jeu, la base est alors créée
3. Stop `create_dataset` program with `Ctrl-C` in terminal.

### puis Entrainement du modèle:
Run `python3 train.py`
### et sous TensorBoard:
Run `tensorboard --logdir=Data/Checkpoints/logs`

### jouer avec Artificial Intelligence:
1. démarrer le jeu (ia déjà entrainée)
2. Run `python3 ai.py` command in terminal.

### This project is still being worked on ... projet en cours et .. ? stoppé en 2019
