# Thème 1 : Le web 

## Le langage Web : Le HTML

1. Donner la signification de HTML
2. Quel est l'histoire de ce langage ? A quoi servait-il ? 
3. Suivre les leçons de la Khan Academy : https://fr.khanacademy.org/computing/computer-programming/html-css


## Thèmes à aborder 

### Les URL
L'URL ( Uniform Ressource Locator ) indique « l'endroit » où se trouve une ressource sur un ordinateur.<br>

Dans la barre d'adresse de votre navigateur web vous trouverez, quand vous visitez un site, des choses du genre : "http://www.ac-grenoble.fr/disciplines/informatiquelycee/index.html". 

La partie "http" est le protocole <br>
La partie "www.ac-grenoble.fr" est l'adresse symbolique (que l'on reverra dans le thème INTERNET) <br>
La partie "/disciplines/informatiquelycee/index.html" s'appelle une URL, c'est le chemin de la page demandée à partir de la racine du domaine ac-grenoble.fr<br>

Une URL permet d'identifier une ressource (par exemple un fichier) sur un réseau. <br>
Un fichier peut se trouver dans un dossier qui peut lui-même se trouver dans un autre dossier... On parle d'une structure en arborescence, car elle ressemble à un arbre à l'envers : <br>
![URL](./Images/web-arborescence.png)<br>

ou schématiser : 

![URL](./Images/web-url.jpeg)<br>


### Les cookies 

Une petite vidéo :

https://dai.ly/x16lt53


### Les clients / serveurs 

Deux ordinateurs en réseau peuvent s'échanger des données. Dans la plupart des cas ces échanges ne sont pas "symétriques" : en effet un ordinateur A va souvent se contenter de demander des ressources (fichiers contenant du texte, photos, vidéos, sons...) à un ordinateur B. L'ordinateur B va lui se contenter de fournir des ressources à tous les ordinateurs qui lui en feront la demande. On dira alors que l'ordinateur A (celui qui demande des ressources) est un client alors que l'ordinateur B (celui qui fournit les ressources) sera qualifié de serveur. <br>

Sur internet, ce modèle client/serveur domine assez largement, même s'il existe des cas où un ordinateur pourra jouer tour à tour le rôle de client et le rôle de serveur (exemple le "peer to peer", voir le module "Internet"), très souvent, des ordinateurs (les clients) passeront leur temps à demander des ressources à d'autres ordinateurs (les serveurs) . Par exemple, comme expliqué dans l'exemple ci-dessus on retrouve cet échange client/serveur à chaque fois que l'on visite une page web. Il y a de fortes chances pour que votre ordinateur personnel joue quasi exclusivement le rôle de client (sauf si vous êtes un adepte du "peer to peer").<br>

N'importe quel type d'ordinateur peut jouer le rôle de serveur, mais dans le monde professionnel les serveurs sont des machines spécialisées conçues pour fonctionner 24h sur 24h. Ils peuvent aussi avoir une grosse capacité de stockage afin de stocker un grand nombre de ressources (vidéos, sons,...).<br>

Afin assurer une continuité de service, dans les sociétés, plusieurs serveurs assurent exactement le même rôle (on parle de redondance). Vous vous doutez bien que Google ne possède pas qu'un seul serveur, en effet, en moyenne, chaque seconde, c'est environ 65000 clients qui se connectent aux serveurs du moteur de recherche de Google. Aucun serveur, même extrêmement performant, ne serait capable de répondre à toutes ces requêtes. Google, Amazon ou encore Facebook possèdent un très grand nombre de serveurs afin de pouvoir satisfaire les demandes des utilisateurs en permanence. Ces entreprises possèdent d'immenses salles contenant chacune des centaines ou des milliers de serveurs (ces serveurs sont rangés dans des armoires appelées "baie serveur"). <br>


![Serveurs](./Images/baie-serveur.jpg)<br>

### Web Statique / web dynamique

1. Donner un exemple de page web statique
2. Donne un exemple de page web dynamique
3. Quelle est l'utilité d'un web dynamique par rapport au statique ?
4. Quel langage permet de rendre la page web dynamique ? 

### RGPD

1. Quelle est la signification du sigle RGPD ?
2. Lister quelques exemples d'utilisation.
3. Quelles sont les conséquences sur internet ?


### Le protocole HTTP 


