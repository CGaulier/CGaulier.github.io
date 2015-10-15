# TP CMS

TP réalisé via virtualBox 

Eleve : Clemence Gaulier 

But : 
  - installer Jekyll et ses prérequis
  - utiliser GitHub

### 1.Installer Jekyll

Jekyll : C'est un service pour créer des site web statique.

Pour installer Jekyll il faut Ruby, Ruby gem et node.js
* Ruby : ruby est un langage et un compilateur crée par Yukihiro Matsumoto. NOTE : ne pas oublier les paquets de développement, sinon jekyll ne s'intallera pas.
* Rubygem : rubygem est un programme permettant d'installer et de lancer des programme ruby. installation via le terminal
* Nodejs : Node js est une plateforme server en javascript.
* commande importante : sudo apt-get install ""

Creation du site :On entre les première ligne de commande de Jekyll new(nom du site) attention à bien se placer dans le bon fichier après la creation du site ! il faut pour le voir en local faire : 
* cd (nom site)
* jekyll serve (ctrl c pour quitter), ensuite 127.0.0.1:4000 (4000 est le port utilisé)


### GitHub

GitHub est un service web pour héberger et pour developer.
inscription a github.io: pour pouvoir travailler en équipe sur des projets web.
installation de git sur le terminal, 
on configure git en suivant les instructions: mettre le nom, le mot de passe etc... NOTE : le nom doit avoir l'extension github.io.
 On crée un fichier pour y mettre notre site (mkdir truc/)
on y clone le repository
* NOTE : à chaque ajouts de fichiers, modifications, etc, il faut appeler github : **git add –all**, 
 **git commit -m « Initial commit »** puis 
**git push -u origin master**

On regarde si le site jekyll qu'on aura crée dans le fichier de git est visible via l'adresse fourni par github dans « settings ». il faudra peut être attendre un peu.

On reprend les instructions de créations de Jekyll mais dans le dossier de votre nom GitHub.

### Bilan : 
on acquiert un site en local et en prod'. On se familiarise avec un outil collaboratif de production également.



