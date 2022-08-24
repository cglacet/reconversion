# Reconversion vers l'informatique

Pense à remettre en question tout ce je te conseille, envoie la page à d'autres informaticiens pour qu'ils puissent te dire avec quoi ils sont daccord ou non. Plus tu auras d'avis différents plus tu pourras t'en faire un bon. Le seul conseil dont je suis sûr c'est : va en priorité vers ce qui te plait à un moment donné parce que si tu es intéressé ça sera beaucoup plus simple de progresser.

## FAQ

### C'est quoi l'informatique ?

Pas mieux que cette vidéo pour résumer : [Exact Instructions Challenge - THIS is why my kids hate me. | Josh Darnit](https://www.youtube.com/watch?v=cDA3_5982h8&t=6s)

### Par où commencer ?

Probablement suivre un cours en ligne, j'ai cherché un peu voir ce que je trouvais mais je pense que c'est très personnel, il faut surtout que les profs soient intéressants à écouter pour toi. Celui là m'a paru sympatique [Harvardx CS50](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x) il en fait un peu trop, mais c'est peut être une bonne chose. En général je crois que les deux principaux pour les cours en ligne c'est [edX](https://www.edx.org/) et [Coursera](https://www.coursera.org/). Si jamais tu trouves un cours bien hésite pas à me l'envoyer. En parallèle ça peut être bien de faire des choses par soi-même, comme tu disais sur des sites d'exercices :

* [Exercism](https://exercism.org/) Celui que j'aime vraiment bien car il y a des mentors prennent le temps de t'écrire pour t'aider à progresser. Visiblement ils ont changé pas mal de choses depuis mon époque mais ça a plutôt l'air mieux. D'ailleurs je vois qu'ils ont ajouté une option pour être mentoré par un ami, si à l'occasion tu veux que je regarde n'hésite pas.
* [Leetcode](https://leetcode.com/problemset/all/?sorting=W3sic29ydE9yZGVyIjoiQVNDRU5ESU5HIiwib3JkZXJCeSI6IkRJRkZJQ1VMVFkifV0%3D) Probablement celui dont tu parlais, je pense que c'est sympa aussi, j'ai très peu testé donc je connais pas bien la difficulté.

Il y en a pleins d'autres, j'avais testé un jour un truc où c'est un genre de jeu avec des unités qui se déplacent mais je suis pas sûr du nom, peut être ça [CodinGame](https://www.codingame.com/start), je suis pas certains que ce soit le plus adapté, mais j'ai jamais expérimenté en tant que débutant. Si t'essayes un jour je serais curieux de savoir ce que t'en as pensé. 

### Quels langages ?

Je pense que ça a assez peu d'importance, le plus important c'est de comprendre un langage aussi bien que possible. Certains disent qu'il vaut mieux commencer par un langage facile d'accès, d'autres pensent qu'il vaut mieux un langage qui ne t'aide pas trop et t'oblige à comprendre les rouages de la machine un peu mieux. Moi je suis pas certain, d'instinct j'opterai plutôt pour un langage simple d'accès, quitte à revenir sur des fondamenteaux (de l'informatique) plus tard. Après il y a un avantage à choisir un [langage populaire](https://survey.stackoverflow.co/2022/#section-most-popular-technologies-programming-scripting-and-markup-languages) car ça facilitera ta recherche de boulot ensuite, ça permet aussi de trouver plus de ressources (cours, tutos, exercices, questions/réponses, ...). L'inconvénient c'est qu'il y a pleins de "tendances" et ça bouge tout le temps, ça peut être perturbant mais il faut ignorer ça quand on débute. 

Pour info : 

* On dit langage de "haut niveau" quand le langage te donne pleins de raccourcis, c'est ceux que j'appelle "simple" d'accès car ça ressemble plus à notre langue d'humains (= langage naturel). 
* À l'inverse un langage "bas niveau" donne peu de raccourcis, tu dois écrire plus de choses à la main. Ça permet d'être plus précis, d'avoir un meilleur contrôle sur les performances par exemple.

Dans les choix que je conseillerai, dans l'ordre :

* [javascript](https://exercism.org/tracks/javascript)/[typescript](https://exercism.org/tracks/typescript) car c'est LE langage par excelence sur le web. On peut absolument tout faire avec. C'est un des langage qu'on utilise le plus dans notre boite aujourd'hui. Tu verras pleins de "dérivés" de javascript (React, Angular, Nodejs, etc.), pour le moment pas besoin de comprendre la différence entre ces "choses" là, mais si un d'eux attire ton attention à un moment, n'hésites pas à te plonger dedans. Nous on utilise principalement React Native, qui est encore une fois du javascript, mais dont le but principal est le développement d'application mobiles. La différence entre typescript et javascript je te laisse la découvrir par toi-même avec le temps :)
* [python](https://exercism.org/tracks/python) c'est un langage qui est de plus en plus utilisé, qui est très facile d'accès. Il est également utilisé dans le web mais uniquement [côté serveur](https://www.wikiwand.com/en/Client%E2%80%93server_model). Par contre il est très utilisé dans le monde de la science des données (data-science) au sens très large (ça inclut le [*machine learning*](https://www.wikiwand.com/en/Machine_learning)). C'est aussi un langage qu'on utilise dans la boite, aussi bien pour nos serveurs web que pour faire des statistiques pour nos clients.
* [Java](https://exercism.org/tracks/java) ou [C#](https://exercism.org/tracks/csharp) (pronnoncé "C-sharp"), je ne connais pas assez bien les deux pour donner un avis très éclairé, mais de mon point de vue ces deux là sont très proches et en général une entreprise qui utilise l'un n'utilisera pas ou peu l'autre. Comme python, sur le web ces deux langages sont uniquement utilisés côté serveur. En général ils sont aussi utilisés par des boites qui font des applications "lourdes" (en gros il faut installer quelque chose sur ta machine pour l'utiliser, en opposition à une application web qui permet aux client d'accéder directement à ton service). Dans ce cas il y aussi un côté design d'interface graphique. En python ça existe aussi mais je n'ai jamais entendu une seule boite faire un client lourd en python. Le type d'application que font ces boites, en général ce sont des applications de gestion/compta et autres outils interne de grosses boites.
* [C](https://exercism.org/tracks/c) pour le coup je ne connais que par l'école, il est utilisé pour faire des applications performantes (du calcul pur et dur par exemple) ou de l'embarqué (du code pour des véhicules, du matériel de mesure, des scanettes de super marché, ... en gros tous les trucs où tu n'as pas d'ordinateur à proprement parlé mais plutôt un outil automatisé, c'est souvent du C). C'est un secteur plus petit que celui du web, mais ça reste un très gros marché. Par contre souvent dans les boites où ils font de l'embarqué c'est vraiment plus dur d'être recruté car ils vont souvent demander des diplômes spécifiques (en particulier à Bordeaux on a Dassault et Thalès qui sont les deux plus gros employeur en C, mais ils sont aussi très exigeants quant aux profils des candidats). Après c'est toujours intéressant de connaitre le C car c'est aussi un langage qui se retrouve dans d'autre. Par exemple, en python il arrive que certains bouts de code aient besoin d'être optimisés (calculs complexes), dans ce cas on est des fois bloqué car python ne nous offre pas ce qu'on cherche et on doit écrire des bouts de code en C. En gros on a du code python qui fait appel à du C pour faire un calcul (en réalité python ne fait que ça, sous le capot, python c'est en fait un [langage "de script"](https://www.wikiwand.com/en/Scripting_language) qui fait appel à du code écrit en C). C'est aussi intéressant car c'est un langage bas niveau qui permet (nottament) de mieux comprendre comment marche la mémoire d'un ordinateur ou même de mieux comprendre des concepts comme les types, les variables et d'autres fondamentaux (qui restent des choses sur lesquelles tu apprendras pendant des années de toute façon, aucune urgence à comprendre ces concepts dans leur intégralité, c'est hyper vaste et très complexe). 

### Si le code fonctionne alors c'est bon

Non. 

### Si le code fonctionne et que ça va super vide, là c'est bon !

Non. Il y a une phrase que j'aime bien bien qui explique pourquoi : 

> Programs are meant to be read by humans and only incidentally for computers to execute. — Donald Knuth

Un programme ilisible finira irémédiablement à la poubelle. En gros il faut voir le code comme quelque chose de vivant, on écrit jamais le code parfait tout de suite, on change d'avis, on fait des erreurs, on veut ajouter de nouvelles choses etc. Et donc, on modifie toujours le code qu'on a écrit par le passé. Si le programme est mal foutu, dur à lire, voir incompréhensible alors la personne qui doit le modifier va juste le réécrire. Ou pire, elle risque de tenter de modifier sans vraiment le comprendre et donc instaurer de nouveaux bugs.

Ce que cette phrase veut dire c'est que le style est important, écrire du bon code c'est très très difficile, il faut s'y mettre dès le début en se disant que tu essayes en fait d'expliquer ce que tu veux faire à un autre humain moins bon que toi avec ton code.

Dans la même veine il y a le [Zen de python]([https://www.wikiwand.com/en/Zen_of_Python](https://www.wikiwand.com/en/Zen_of_Python#/Principles)) qui est un genre des dix commandements du code selon les créateurs du langage python.

### Apprendre à utiliser Linux ?

Pas obligé, mais si tu es curieux n'hésites pas car aujourd'hui c'est très accessible (car proche de l'interface windows, par exemple [ubuntu](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview)). C'est toujours un plus de connaitre un peu linux (et les rudiments du [bash](https://towardsdev.com/why-learn-bash-scripting-e47823a1f313)). Moi je n'utilise que Linux (mac en vrai, mais c'est presque pareil, notamment sur le fait que j'utilise bash tous les jours au boulot).

### Quel(s) logiciels ? 

Aujourd'hui tu n'as presque besoin que de [vscode](https://code.visualstudio.com/) (un éditeur de texte fait pour le developpement). Il y a des alternatives, mais honnêtement j'en suis très content. Aussi, je te conseille de te mettre assez tôt à [Git](https://git-scm.com/), au départ fait toi aider par quelqu'un si tu as du mal. C'est un outil qui te permet d'avoir un historique de ton code (et une sauvegarde sûre aussi en général). Une équipe de developpeurs utilise toujours un outil de versioning pour permettre de travailler à plusieurs sans perdre des bouts de travail. Je sais pas si tu as déjà eu des expériences avec des gens qui s'échangent des document word par mail (`compte_rendu_v32_michel.docx`) mais c'est justement ça qu'on veut éviter avec Git. En gros tu as un serveur (tu connais peut être déjà github, c'est le site sur lequel tu lis ce message) qui contient tout l'historique de l'application et les développeurs ont une copie (plus ou moins complète) de cet historique sur leur machine personnelle. Quand le developpeur fait un changement sur sa machine, il récupère l'historique qui est automatiquement fusioné avec ses changements locaux, puis il publie l'historique mis à jour (bon en pratique des fois la fusion n'est pas automatique, mais dans un premier temps comme tu travailleras seul ça le sera, tu auras le temps d'apprendre les bases de Git sans te soucier de ces complications). Quand on fait une modification de le code, sur git on peut (/doit) aussi attacher un message qui explique la modification qui vient d'être faite (des messages court comme "Add feature X" ou "Fix bug Y"). Il y a d'autres outil de versioning, mais quasiment tout le monde utilise Git. 


# Conseils en vrac

* Si possible, trouve une idée de projet perso qui te donnera un objectif autre qu'apprendre des choses en vrac. À mon avis, dès que tu as fini un premier cours en ligne, tu peux te lancer dans un projet perso. L'idéal c'est d'avoir un projet qui ait l'air aussi con que possible, plus c'est simple mieux c'est. Dès que tu commences il faut que ton projet soit fonctionnel, ça te motivera. Par exemple, si tu veux faire une page web, il faut que tu trouves de l'aide pour rendre une page web (vide) disponible à tout le monde. Puis de là, tu pourras ajouter des choses, petit à petit en mettant à jour ta page au fur et à mesure. Le site web c'est une des options, mais pas la seule du tout. Des projets pour fabriquer des petits utilitaire pour toi (sur ta machine) c'est aussi une très bonne piste. Pour te donner une idée, avec un pote pour s'amuser on a fait un "bot" qui va chercher des clips sur twitch et fait des vidéos youtube tout seul (il publie 2 fois par jour, tous les jours sans qu'on ne fasse rien). Par rapport à ce que je disais sur le côté "simple" du projet que je te conseillerai de faire, ce "bot" est un peu trop complexe. Même si quand je le dis ça a l'air con, dit toi que c'est déjà au moins 20h de boulot qu'on a dû mettre à deux pour y arriver, et le bot est loin d'être un projet propre. Pour un projet pour commencer il faut viser vraiment plus simple, si un jour tu as une idée tu me dis et je trouverai moyen de simplifier ton idée pour que tu aies un but atteignable et surtout un projet que tu peux finir de A à Z en ayant un contrôle total sur ce que tu fais. 
* Si tu ne comprends pas quelque chose pense à chercher la même information écrite par quelqu'un d'autre, voir à demander de l'aide à quelqu'un pour t'expliquer. Des fois il est juste trop tôt pour comprendre quelque chose (il y a un concept sous-jacent que tu ne connais pas encore ou que tu as mal compris), il faut aussi savoir se dire qu'on a pas tout compris mais que c'est pas grave. Idéalement tu peux garder une liste des choses que tu n'es pas sûr d'avoir bien comprises ou même des choses que tu as ignoré en te disant que c'était trop tôt/pas pour toi, etc. 
* Partage tout ce que tu fais, même si c'est nul on s'en fout, plus de gens voient ce que tu fais plus tu auras de bons conseils. 
* Ne jamais prendre une remarque sur ton code pour toi, sinon tu n'en finiras jamais car on écrit tous du code de merde. C'est d'ailleurs un bon moyen de voir si tu progresses, si quand tu regardes ton code d'il y a un mois et que tu te dis "waahh c'est affreux comment j'ai pu écrire ça" c'est que tu es sur la bonne voie. D'ailleurs un très bon article du mec qui a créé stackoverflow à ce sujet [The Ten Commandments of Egoless Programming](https://blog.codinghorror.com/the-ten-commandments-of-egoless-programming/)
* Toujours se méfier des certitudes et des évidences (des tiennes et aussi de celles des autres).


# Formations et diplômes

Aujourd'hui ça reste difficile de trouver un job bien payé sans diplôme (ou équivalence). 

## CNAM

* [DEUST Informatique d'organisation et systèmes d'information](https://www.cnam-nouvelle-aquitaine.fr/diplome,deust-informatique-d-organisation-et-systemes-d-information-iosi-technicien-developpement-securite-et-exploitation,DUS0501A)
* [Licence 3 : Informatique générale et cybersécurité](https://www.cnam-nouvelle-aquitaine.fr/diplome,licence-3-informatique-generale-et-cybersecurite,LG02501A-2)
* [Licence 3 : Informatique développement objet et Web](https://www.cnam-nouvelle-aquitaine.fr/diplome,licence-3-informatique-developpement-objet-et-web,LG02501A-3)
