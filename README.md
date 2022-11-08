                                                                                                 Numérique et Sciences Informatiques 1ère


## Chapitre 4 Interractions Homme-Machine sur le WEB (IHMWeb)


**Ce cours est une copie(modifiée par mes soins pour mes élèves de 1ère NSI) du cours proposé par PR Xavier Blanc Université de Bordeaux** 
[Le lien du cours original](https://github.com/xblanc33/nsi-1ere-web.git)

La figure suivante illustre les deux points du programme.
On voit
(1) les interactions entre l'utilisateur et le navigateur web
(2) les interactions entre le navigateur web et le serveur web.
Le cas particulier des formulaires web permet de montrer les interactions de bout en bout.

![Interactions dans le web](./img/interactions.png)


## Programme du chapitre

Pour couvrir le programme voici l'organisataion des séquences: 

1. [IHMWeb1 Fonctionnement d'un site web de bout en bout](./1-E2E/README.md)
2. [IHMWeb2 HTML ou comment structurer l'information contenue dans un site web](./2-HTML/README.md)
3. [IHMWeb3 Interaction Utilisateur / Navigateur Web, exploitation de JavaScript (DOM et Event)](./3-Navigateur/README.md)
4. [IHMWeb4 Interaction Navigateur Web / Serveur Web, comment le client interagit avec le serveur ?](./4-Serveur/README.md)
  
Pour aller plus loin, on pourra traiter des points suivants:
* Le style des pages web avec CSS
* Préservation de la vie privée sur le web : les cookie
* Authentification et confidentialité sur le web : HTTPS et autres mécanismes



## Rappel du programme

Le programme précise les contenus suivants:

| Contenus | Capacités Attendues | Commentaires |
|----------|---------------------| ------|
| <p>Modalités de l’interaction entre l’homme et la machine</p> <p>Événements</p> | <p>Identifier les différents composants graphiques permettant d’interagir avec une application Web.</p> <p>Identifier les événements que les fonctions associées aux différents composants graphiques sont capables de traiter.</p>| Il s’agit d’examiner le code HTML d’une page comprenant des composants graphiques et de distinguer ce qui relève de la description des composants graphiques en HTML de leur comportement (réaction aux événements) programmé par exemple en JavaScript.|
| <p>Interaction client-serveur.</p> <p>Requêtes HTTP, réponses du serveur</p>| <p>Distinguer ce qui est exécuté sur le client ou sur le serveur et dans quel ordre.</p><p>Distinguer ce qui est mémorisé dans le client et retransmis au serveur.</p> <p>Reconnaître quand et pourquoi la transmission est chiffrée.</p> | <p>Il s’agit de faire le lien avec ce qui a été vu en classe de seconde et d’expliquer comment on peut passer des paramètres à un site grâce au protocole HTTP.</p>|
|<p>Formulaire d’une page Web</p> | <p>Analyser le fonctionnement d’un formulaire simple.</p><p>Distinguer les transmissions de paramètres par les requêtes POST ou GET.</p>| <p>Discuter les deux types de requêtes selon le type des valeurs à transmettre et/ou leur confidentialité.</p>
