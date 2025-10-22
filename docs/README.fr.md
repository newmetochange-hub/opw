# OPW : Une architecture comportementale vivante pour l’ère post-serveur

![Logo OPW](../logo/opw-logo.svg)

> Un langage pour les développeurs qui en ont assez de se battre avec la structure—et qui veulent parler en comportements.

---

## 🧠 Pourquoi OPW ?

Les systèmes classiques frappent encore :
- APIs centrales, injections manuelles, charges lourdes, logique répétée  
- Des développeurs noyés dans la documentation pour comprendre les flux de base  
- Des serveurs saturés par des requêtes redondantes

On a dit : stop.

---

## 🚀 Qu’est-ce que OPW ?

OPW est un langage comportemental—not un framework, ni un outil, ni une classe.

Avec une seule ligne, le développeur déclare simplement son intention :

```bash
opw add login auth smsotp parsgreen

Et le système comprend :
- Quelle est la fonction mère
- Quelles fonctions enfants doivent être injectées
- Quelles dépendances sont nécessaires
- Comment les combiner

🧩 Concepts clés
- Fonction mère : définit le chemin comportemental, pas l’exécution
- Fonctions enfants : injectées depuis la mémoire centrale, composables et remplaçables
- opw_pack : enveloppe comportementale qui décrit ce qu’est la fonction, ce dont elle a besoin, et comment elle se connecte
- Mémoire centrale : connaît tout—ce qui existe, comment ça se connecte, et ce qui doit être exécuté

☁️ Serverless : Un exécutant, pas un architecte
Dans OPW, les chemins comportementaux deviennent des endpoints serverless :
GET https://mygod.com/login → auth → login → user_login()


- Comportements légers (ex. lecture d’articles) → serveurs edge avec TTL court
- Comportements lourds (ex. connexion + achat + suivi) → serveurs centraux avec cache et file d’attente

🏢 Grandes entreprises : Collaborateurs sous contrôle
- Elles peuvent créer des middlewares privés pour leurs fonctions propriétaires
- Seules elles y ont accès
- La logique partagée (celle enfouie dans les docs) va dans la mémoire centrale
- Le développeur n’a plus besoin de lire des kilomètres de documentation—il déclare simplement ce qu’il veut

🔥 Pourquoi c’est important
Parce qu’on ne cherche pas la perfection.
On construit une architecture vivante—compréhensible, composable, négociable.
OPW n’est pas un framework.
C’est un langage pour la composition comportementale, la négociation, et la croissance.

🌐 Traductions
- English
- فارسی
- العربية

🤝 Contribuer
Ce n’est que le début.
Si OPW vous parle, aidez-le à grandir.
Ouvrez une PR, partagez vos idées, proposez de nouveaux comportements—ou mettez simplement une étoile pour nous dire que vous êtes là.
