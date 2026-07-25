
<p align="center"> <img src="https://circafrax.github.io/assets/banniere.png" width="500"> </p>


CodexDevBetaTest - Kit du bêta-testeur (https://circafrax.github.io/beta-test/index.html)
<p align="center">
🧪 Ouvrir l'outil de compte rendu (en ligne)
100% offline, rien ne part tant que tu ne postes pas ton .md

</p>
Les plus simples outils devraient rester carrés.
Pas besoin de pavé Word pour dire qu'un bouton est flou. Juste un outil qui ne laisse rien oublier.

CodexDevBetaTest c'est le petit utilitaire que j'aurais voulu donner à mes testeurs depuis le début. Fini les rapports à la main où il manque la version, l'OS ou la capture.

C'est l'anti-formulaire Google. Pas de cloud. Pas de compte. Tu ouvres, tu coches, tu exportes en .md et tu le poses sur GitHub.

## Aperçu

<img src="https://github.com/CircaFrax/beta-test/blob/main/assets/screenshot.png" width="650">
*À gauche tu remplis, à droite tu as le .md prêt pour GitHub – 100% offline*

Philosophie : Un rapport = Un fichier
Comme les autres Codex : 1 outil = 1 fichier.

Pas de base de données. Pas de tracker. Juste un .md qui va dans /reports.

📖 Utilisation
Pour le bêta-testeur (2 min)
Ouvre https://circafrax.github.io/beta-test/index.html
Remplis :
Infos générales : nom, logiciel, version, date, plateforme
Installation / Interface / Boutons : notes 1 à 5 + remarques
Observations rapides : clique sur + Ajouter une ligne -> choisis Bouton, Design, Action... et écris ta remarque à côté
Fonctionnement + Recommandations
Clique Télécharger .md
Le fichier se nomme tout seul : 2026-07-24_nom-du-testeur_logiciel-v0.4.3.md
Envoie-le ou dépose-le dans le dossier reports/ du repo
Pour le dev

Tous les rapports arrivent en .md dans /reports avec ce nommage :
reports/2026-07-24_astra_codexgenqrcode-v0.4.3.md
Triable par date, lisible direct sur GitHub.

```
📁 Structure du kit
beta-test/
├── index.html          # L'outil complet (CodexDevBetaTest)
├── README.md           # Ce fichier
└── reports/            # Tous les comptes rendus .md
    ├── 2026-07-24_astra_codexgenqrcode-v0.4.3.md
    └── 2026-07-25_testeur_codex-v1.md
```

✍️ Modèle de rapport généré
L'outil génère exactement ça, rien à inventer :

md
# Compte rendu de bêta-test

## Informations générales
- Testeur : ...
- Logiciel : ...
- Version : ...
- Date : ...
- Plateforme : ...

## Installation
- Facilité d'installation : ...
- Problèmes rencontrés : ...

## Interface / design
- Clarté : ...
- Lisibilité : ...
- Cohérence visuelle : ...
- Remarques : ...

## Boutons / navigation
- Boutons compréhensibles : ...
- Réactions attendues : ...
- Ergonomie : ...
- Remarques : ...

## Observations rapides
| Type | Commentaire |
|---|---|

## Fonctionnement général
- Ce qui marche bien : ...
- Ce qui bloque : ...
- Bugs trouvés : ...

## Recommandations
- Améliorations suggérées : Ajout de plusieurs OS en selection.
- Priorité : ...

🔒 Confidentialité
Zéro réseau : l'outil tourne dans ton navigateur, même en file://
Zéro envoi auto : rien ne part tant que tu ne postes pas toi-même ton .md
📄 Licence
CircaFrax Proprietary Freeware - Libre pour tous, comme tous les Codex

Fait partie de la suite Codex — des logiciels qui s'utilisent sans installation, comme en 1998, mais en mieux.

