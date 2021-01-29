# Answers

Nom : NDIAYE
Prénom : Die Aïssatou 

# 1.
Qu'est-ce qu'une instance EC2 ?
Amazon Elastic Compute Cloud ou EC2  permet de créer des instances dans le cloud.Ces instances sont des machines virtuelles qui peuvent peut être utiliser pour développer, déployer et/ou installer des applications ou des serveurs.

# 2.
Qu'est-ce qu'un VPC ?
C'est un réseau privé virtuel dans le cloud.

# 3.
A quoi sert un NSG ?
Permet de gérer la sécurité d'un VPC.

# 4.
Quelles sont les 5 propriétés désirables du cloud ?
1. Les fonctions sont instanciées en fonction des besoin du moment, a la demande 
2. Une securite sure
3. Toujours accessible
4. Paiement de seulement ceux que l'on consomme
5. Libere contrainte de maintenance


# 5.
Qu'est-ce que l'A/B Testing ?
C'est une technique qui permet d'utiliser deux versions differentes d'une application afin de tester leur perfomance. 
Lors des changements de versions il peut arriver qu'il ait un soucis, alors cette technique nous permet de garder 
l'ancienne version qui fonctionnait auparavent.

# 6.
Comment programmer le cloud ?
J'ai pas compris la question.

# 7.
Quelle est la technique pour faire un déploiement sans interruption de service ?
C'est la technique du blue/green deploiement.
# 8.
Qu'est-ce que le Canary release ?
C'est une technique de deploiement. Elle consiste a avoir deux versions d'une même application.
De sorte qu'on puisse travailler sur une des versions pour faire des tests et l'autre reste deployé pour les utilisateurs.

# 9.
Comment changer de taille de machine virtuelle ?
Il faut changer alors le type de l'instance qui défint toujours la mémoire de la CPU et de la mémoire de stockage. L'un ne va pas sans l'autre.

# 10.
Qu'est-ce que le Blue/Green deployment ?
ça consiste à avoir deux environnemnts de travail identique. Dans l'un nous avons notre application de base (Blue) que les utilisateurs utilisent.
Puis si on souhaite deployé une nouvelle version(Green) par exemple, on le fait dans le deuxieume environnement puis nous avons juste à router 
les clients vers le nouveau environnement. 
