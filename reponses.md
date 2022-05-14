## Réponses

1. "*Qu’est-ce que maven ?*"
    > Maven est un outil de build pour java, permettant de gérer les dépendances à partir d'une source de packages.
1. "*Quelle est l’arborescence d’un projet d’une application web utilisant maven ?*"
    > pom.xml
    > src
    > > main
    > > > java
    > > > > *namespace*
    > > > > > *fichiers .java...*
    > > >
    > > > resources
    > > > > *namespace*
    > > > > > *images, ressources binaires...*
    > >
    > > test
    > > > java
    > > > > *namespace*
    > > > > > *fichiers .java...*
    > > >
    > > > resources
    > > > > *namespace*
    > > > > > *images, ressources binaires...*
1. "*Citer 2 autres outils « concurrents » de maven*"
    > - [Gradle](https://gradle.org)
    > - [Apache Ant](https://ant.apache.org)
1. "*Qu’est-ce que le « TDD » ?*"
    > *Tests driven developpement*, le but est d'écrire des tests unitaires avant d'écrire le code source du programme, afin de dès le départ assurer le bon fonctionnement du code source écrit par la suite.
1. "*Quels sont les principes « SOLID » ?*"
    > - Une classe ne doit faire qu'une seule chose. (Une tasse de thé ne doit pas faire du café).
    > - Une classe ne doit pas être directement modifiée, mais uniquement rajouter des fonctions/méthodes.
    > - Toute méthode réécrite de classe héritant d'une autre classe doit toujours respecter la signature de la méthode mère (globalement forcé dans tout langage fortement typé).
    > - Une classe ne doit pas hériter d'une autre classe ou interface illogique (une tasse de thé ne doit pas implémenter une interface du type `CoffeFactory`, qui aurait une méthode `makeCoffee()`).
    > - Une classe doit demander autant que possible des types abstraits (dans les paramètres de méthode, une classe abstraite ou une interface) correspondant au strict nécéssaire.
1. "*Citer 3 serveurs d’applications java*"
    > - Tomcat
    > - Glassfish
    > - Jetty
1. "*Dans quel fichier se trouve la configuration des servlets d’une application web ?*"
    > La configuration des servlets se fait via les packages `javax.servlet` et `javax.servlet.http`.
1. "*Donner une rapide définition de REST*"
    > REST est une convention de communication entre client-server basés sur certains principes (endpoint d'url et protocole explicite, langage commun XML/JSON/...).
1. "*Quelles sont les 3 directives spécifiées par les spécifications des JSP ? (les citer et indiquer leurs rôles)*"
    > - *page* : permet de définir des options de configuration
    > - *include* : permet d'inclure des fichiers statiques dans la JSP avant la génération de la servlet
    > - *taglib* : permet de définir des tags personnalisés
1. "*Donner une rapide définition de ORM*"
    > Technique de programmation informatique qui crée l'illusion d'une base de données orientée objet à partir d'une base de données relationnelle en définissant des correspondances entre cette base de données et les objets du langage utilisé. On pourrait le désigner par «correspondance entre monde objet et monde relationnel ».