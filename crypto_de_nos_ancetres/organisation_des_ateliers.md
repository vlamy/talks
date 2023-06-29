# Organisation de chaque atelier

- Historique de la méthode : qui, quand, pourquoi ?
- Fourniture du message à déchiffrer et des outils, mais sans indiquer comment s’en servir  
- Solution et regard critique sur la performance de la méthode de chiffrement présentée  

## Introduction générale

Bonjour à tous et merci de votre présence ici pour revivre la cryptographie de nos ancêtres, celle d’avant l’ère informatique. 
Car oui, le besoin de pouvoir échanger des messages de manière confidentielle date de plus de 2000 ans.  

Comme pour beaucoup de domaines, c’est un besoin né d’affaires politiques et militaires qui a conduit à l’élaboration de méthodes de chiffrement toujours de plus en plus robuste à mesure que celles-ci se voyaient cassées par les ennemis.

## La scytale

Un outil en ligne pour chiffrer facilement les messages : https://www.apprendre-en-ligne.net/crypto/transpo/scytale.html.  

### Historique

La scytale est l'un des plus anciens systèmes de chiffrement de messages, et date d'au moins l'an 400 avant notre ère.  
Selon les récits de Plutarque, elle a été utilisée par Lysandre de Sparte lors de la guerre du Péloponnèse opposant Sparte à Athènes.  

### Atelier

Je vois plusieurs façons de le faire :  

1- On donne les scytales et le texte chiffré (mais pas sur un ruban, plutôt sur des feuilles imprimées et plastifiées par exemple). On laisse alors les gens comprendre qu'il faut écrire le texte sur un ruban et l'enrouler autour de la scytale pour le déchiffrer  
2- On donne les rubans, sans les scytales, les laisse chercher puis ensuite on donne les scytales  
3- On porte toi et moi des rubans en guise de ceinture, comme à l'époque, et on dit aux gens "nous portons chacun sur nous un message chiffré", puis une fois qu'ils ont trouvé les rubans on retombe sur la proposition 2  

### Solution de l'atelier et regard critique

- Explication du fonctionnement  
- Démonstration de la faiblesse du chiffrement, puisqu'il suffit d'écrire le message sur plusieurs lignes et de lire en colonnes pour le décrypter (ou l'inverse, ça fonctionne aussi)  

## Le chiffre de César  

### Historique  

Comme son nom l'indique, il a été utilisé par César afin de préserver le secret de ses correspondances, qui l'utilisait de plus avec l'alphabet grec, obscur pour les gaulois mais parfaitement maîtrisé par l'élite romaine.

### Atelier  

- On donne le texte en alphabet grec  
- Comme on est sympas, on donne la table de traduction grec -> latin  
- Finalement, on indique que c'est un chiffrement par substitution, et finalement la solution  

### Solution de l'atelier et regard critique

- Explication du fonctionnement  
- Wikipédia : *Le chiffre de César fut encore employé en 1915 : l'armée russe le préférait à d'autres codes plus élaborés mais qui s'étaient révélés trop difficiles d'utilisation pour leurs troupes ; les analystes allemands et autrichiens eurent peu de mal à déchiffrer leurs messages*  
- Divers modes d'attaque : le plus performant est l'analyse fréquentielle, pour peu que l'on connaisse la langue dans laquelle le message a été écrit  

## Le chiffre de Vigenère

### Historique

Cette méthode, décrite au XVIè siècle par Blaise de Vigenère, est résistante à l'analyse fréquentielle. Bien qu'il ne soit probablement pas le père de cette méthode, elle a été nommée ainsi en son honneur au XIXè siècle.

### Atelier

### Solution de l'atelier et regard critique

Bien que résistant de prime abord aux attaques par analyse fréquentielle, il est possible d'attaquer par analyse de fréquence les sous-textes formés par les lettres chiffrées par une même lettre de la clé.  
Au XIXè siècle Friedrich Kasiski publie une [méthode de cryptanalyse](https://fr.wikipedia.org/wiki/Cryptanalyse_du_chiffre_de_Vigen%C3%A8re) permettant de déterminer la longueur de la clé par recherche de répétitions de motifs dans le texte chiffré, cassant ainsi cette méthode de chiffrement.

La taille de la clé joue donc un rôle important, plus elle est grande, moins il y a de répétitions de motifs et de données disponibles pour l'attaque par analyse de fréquence.  


## Conclusion

# Todo-list et commentaires

- [ ] Déterminer le nombre de groupes pour les ateliers -> $x$ dans la suite pour le nombre d'éléments à préparer
- [ ] Fabriquer les $x$ scytales
- [ ] Fabriquer $x$ rubans avec des chutes de tissu
- [ ] Imprimer + plastifier $x$ correspondances entre alphabet grec et latin
- [ ] Imprimer + plastifier $x$ messages chiffrés via César
- [ ] Imprimer + plastifier $x$ messages chiffrés via Vigenère (sur les même feuilles que César peut-être ?)
- [ ] Imprimer + plastifier $x$ tableaux de correspondance pour Vigenère
- [ ] Prévoir $x$ feutres pour ardoise


L'avantage des feuilles plastifiées c'est que l'on peut s'en servir comme d'une ardoise avec les feutres.
On peut par ailleurs faire ressembler les feuilles à de vieux parchemins en brûlant les bords comme pour les cartes au trésor de pirates :-P
