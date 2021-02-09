# Projet: Casino
Dans le groupe il y a Matvei, Teïs, Leonardo et Theo
Nous allons partir sur un projet de casino qui comporterai plusieurs jeux qui serais une machine à sous, une roulette et un blackjack.<br/>
Pour la machine à sous:<br/>
-système de multiplicateurs<br/>
-système de mise de somme et de calcul de gains<br/>
Pour le blackjack:<br/>
-système de croupier "intelligent"<br/>
-système de mise : si victoire mise multiplié par 2, si défaite perte de la mise, si égalité le joueur garde sa mise<br/>
Pour la roulette:<br/>
-différents systèmes de pari : par nombre (fois 36), par douzaine (fois 3), de 1 à 18 et de 19 à 36 (fois 2), le rouge et le noir (fois 2), par colonne (fois 3)<br/>
-système de gain par multiplicateur(voir au dessus)<br/>

De plus il y aura un système de connexion géré avec une base de donnée qui comportera pour chaque membre un identifiant, un mot de passe et son argent.<br/>

Il y aura un menu général qui permettra de choisir son jeu, et d'aller dans son profil pour voir son argent, se déconnecter et cahnger son mot de passe.

<br/>Matvei s'occupera de la machine à sous, Leonardinho de la roulette, Teïs du blackjack et Theo de l'interface graphique/coordination entre les jeux

<br/>____________________

<br/>

Pour les contributions de Leonardo et Teis, c'est moi qui apparait comme auteur du commit. C'est normal, j'ai juste ajouté des dossiers et renommé les fichiers pour plus de clarté

<br/><br/>*Installation du casino.*
<br/><br/>Pour lancer le casino, executer le fichier 'casino.py', puis créer un compte ou se connecter. Dans l'interface graphique, la navigation est assez simpliste (cliquer sur les icones). Pour choisir sa mise, d'abord cliquer sur le rectangle et entrer un nombre (pas sur le clvier numérique). Pour effacer un chiffre, cliquer sur 'BACKSPACE'. Lorsque le nombre est choisi, cliquer sur 'RETURN'.
<br/><br/><br/>*Elements fonctionnels.*
<br/><br/>Actuellement, le sysytème de connexion, la machine à sous (même si il n'y a pas d'interface), le profil fonctionnent. On peut parier une mise sur le blackjack mais rien ne se passe après, et on travaille actuellement sur le système de pari pour la roulette.

<br/>PS: il peut arriver que le programme passe certains écrans lorsque deux éléments cliquables sont aux mêmes endroits sur différents écrans.

<br/>____________________


# Les aspects techniques du projet

<br/><br/>

<br/>Nous avons utilisé la biblothèque random à travers tout les programmes et les fonction des jeux car  les jeux de casino sont basé sur l'aléatoire, nous avons pricipalement utilisé random.randint afin de tirer des entiers que nous avons utlilisés afiin de définir sur quoi les jeux tombent (nombre à la roulette, cartes au blackjack et les symboles qui toombent dans la machine à sous).
