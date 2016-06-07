# Présentation de l'organisme


**présentation générale**

Fondée en 1976 lors de la cission de l'université de clermont, l'Université d'Auvergne (UdA) actuellement présidée par Alain Eschalier compte plus de 16 000 étudiants dont 3 000 étrangers rassemblés au sein de 7 composantes :
- École de Droit
- École d'Économie
- École Universitaire de Management
- Faculté de Médecine
- Faculté de Pharmacie
- Faculté de Chirurgie Dentaire
- Institut Universitaire Technologique 
L'université dispose aussi de 22 laboratoirs de recherche

**conditions du stage**
J'ai effectué mon stage au sein du laboratoir EA CIDAM (Conception, Ingenierie et Developpement de l'Aliment et du Medicament)
Dirigé par le professeur M. ALRIC, l'équipe de recherche travaille nottament à comprendre, évaluer et analyser, dans l’environnement digestif, différentes situations physio-pathologiques liées au vieillissement, à la présence de bactéries pathogènes (en particulier d’Escherichia coli entérohémorragiques), ou encore à celle de produits toxiques, de xénobiotiques, en particulier de polluants.
C'est dans ce cadre là que Bérénice BATUT, ma tutrice de stage, dévellope un environnement bioinformatique permettant de faciliter l'analyse de données massives issues du microbiote AsaiM. 


# AsaiM :an environment to analyze intestinal microbiota data

ASaiM (Auvergne Sequence analysis of intestinal Microbiota) est un environnement créé pour analyxer les microbiotes, et plus particulièrement le microbiote intestinal. 



# Galaxy :

Galaxie est une plate-forme ouverte et open source, ses données étant accessibles librement en ligne, permettant d'utiliser simplement de nobreux outils d'analyse via son interface.

On peut accéder à Galaxy de différentes façons. Tout d'abord, il existe plusieurs serveurs publics de galaxy. L'avantage de ces serveurs étant qu'ils disposent souvent d'une importante puissance de clacul. Cependant énormément de personnes utilisent ces serveurs ce qui cause d'important temps d'attentes. De plus un nombre limité d'outils  sont installés sur ces serveurset il y a très peu de chances qu'un administrateur installe des outils si la demande lui est faite par une petite communauté.
Il existe cependant de très nombreux serveurs liés à des laboratoirs ou des entreprises ces serveurs disposent généralement d'une bonne puissance de calcul et les administrateurs sont sencés être disponibles losqu'il s'agit d'ajouter des outils. 
On peu aussi télécharger une instance de Galaxy en local sur n'importe quel ordinateur. Cependant dans ce cas là, il faut gérer soit même l'instalation des outils et la puissance de calcul est limité à celle de l'ordinateur.

Un des avantages de Galaxy est que si vous êtes connectés sur un compte, tous les fichiers d'entrée ou de sortie produit grâce à galaxy sont stockés dans l'historique de l'instance et ne peuvent être définitivement supprimés que par un administrateur. Ainsi même plusieurs mois après, on peut récupérer a nouveau nos données.

Mais l'intérêt majeur de cette instance est de pouvoir lancer des outils de bioinformatque, qui fonctionnent normalement en ligne de commande afin d'effectuer des analyse complètes mais surtout reproductibles grâce aux wrappers, des interfaces faisant le lien entre l'utilisateur et la ligne de commande de l'outil.


