# Evaluation-github

Yann Soulinthavong - Léo Chan

  Dans un premier temps on a cloné le git grâce à la commande "git clone https://github.com/LeoChris88/Evaluation-github.git", puis à l'aide du terminal, on a commencé à initier l'environnement de travail "git init -y" et également "npm install --save-dev jest" qui permet l'installation des modules de jest pour pouvoir faire les tests de fonctionnalités.
  
  Comme indiqué dans la consigne il faut 1 branche par fonctionnalité, c'est pourquoi on a entré la commande git status pour voir dnas quelle branche on se situe et faire "git checkout -b <Nom>" + le nom de la branche où l'on souhaite s'y rendre. 

  Une fois les fonctionnalités testées, on va push les modifications. Pour ce faire, on va "git add ." ( avec un .gitignore sinon on va add toutes les node modules ), puis "git commit -m <commentaire>" et pour finir "git push -u origin <Nom>" + le nom de la branche.

  Du côté de Github, celui qui a fait une modification et a push, il va devoir aller dans la partie Pull requests, cliquer dessus et ensuite faire un merge pull requests. Le binôme va ensuite faire un "git pull origin <nom>" + le nom de la branche.
