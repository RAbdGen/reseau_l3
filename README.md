🧪 TPs Kathara

Ce dépôt contient l’ensemble de mes travaux pratiques (TPs) réalisés avec Kathara, un outil de virtualisation réseau permettant de simuler des topologies et des environnements réseau complets.

⚙️ Prérequis

Avant d’utiliser les labs, veuillez vous assurer que Kathara est installé sur votre machine.
👉 Documentation officielle Kathara

🧭 Structure du dépôt

Chaque TP est organisé dans un dossier séparé.
Par exemple :

.
├── TP1/
│ ├── lab.conf
│ ├── pc1.startup
│ └── ...
├── TP2/
│ ├── lab.conf
│ ├── r1.startup
│ └── ...
└── README.md

🚀 Utilisation

Pour lancer un lab Kathara, suivez les étapes ci-dessous :

Cloner le dépôt :

git clone https://github.com/<votre-utilisateur>/<votre-repo>.git
cd <votre-repo>

Entrer dans le dossier du lab souhaité :

cd TP1

Lancer le lab :

kathara lstart

Tester les différentes machines :

kathara connect <nom_de_la_machine>

Exemple :

kathara connect pc1

Arrêter le lab :

kathara lclean

💡 Conseils

Veillez à exécuter les commandes depuis le dossier du lab correspondant.

Vous pouvez vérifier la topologie avec :

kathara linfo

Si un lab ne démarre pas correctement, essayez :

kathara lclean
kathara lstart

📚 À propos

Ce dépôt a pour objectif de regrouper l’ensemble de mes TPs Kathara, de faciliter leur exécution et de permettre à d’autres utilisateurs de tester les différentes configurations réseau.
Chaque TP contient ses propres fichiers de configuration et scripts de démarrage.
