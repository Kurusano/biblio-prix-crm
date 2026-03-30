<img width="1190" height="825" alt="Capture accueil Bibliothèque de prix" src="https://github.com/user-attachments/assets/fc93e1bb-99e0-4cd1-845f-4677110d6a0c" />Bibliothèque de Prix — CRM
> **Outil interne de consultation des prix de référence pour les marchés publics de menuiseries extérieures.**
![Live](https://img.shields.io/badge/🌐_Application_Live-Accéder-2E75B6?style=for-the-badge)
![Articles](https://img.shields.io/badge/📦_Articles-14_314-1B3A5C?style=for-the-badge)
![Marchés](https://img.shields.io/badge/📋_Marchés-22-1B3A5C?style=for-the-badge)
![Accès](https://img.shields.io/badge/🔒_Accès-Protégé-green?style=for-the-badge)


Aperçu
> *💡 Accès protégé par mot de passe — disponible en interne CRM.*
> <img width="1190" height="825" alt="Capture accueil Bibliothèque de prix" src="https://github.com/user-attachments/assets/a4195710-bf17-4a14-b98f-d37133b6e7a3" />
-<img width="1291" height="915" alt="Capture Bibliothèque de prix - CRM" src="https://github.com/user-attachments/assets/7a38c430-0d3f-48ba-aae8-8162d0178277" />



---
Contexte
Projet développé en alternance chez CRM (Conception Réalisation de Menuiseries) — PME spécialisée en second œuvre bâtiment, Île-de-France.
Problématique : Le chiffrage des BPU en marchés publics reposait sur la consultation manuelle d'anciens devis, fragmentés et non centralisés. Processus long, imprécis, dépendant de l'expérience individuelle.
Solution mise en place : Un référentiel centralisé de 14 314 articles issus de 22 marchés publics en Île-de-France, avec recherche instantanée et statistiques de prix en temps réel.
---
Fonctionnalités
Fonctionnalité	Détail
🔍 Recherche instantanée	Par mots-clés, avec tri par pertinence, prix ou date
📊 Statistiques temps réel	Prix min, max, moyenne, nombre de sources
🗂️ Filtres avancés	Par catégorie, famille, type, marché source
📅 Dates de marché	Code couleur : actif 🟢 / en attente 🔵 / expiré 🔴
📄 Détails déroulants	Descriptions techniques longues accessibles au clic
🌙 Mode clair / sombre	Préférence sauvegardée automatiquement
📱 Responsive	Mobile, tablette et desktop
🔒 Accès sécurisé	Mot de passe hashé SHA-256
⚡ PWA	Installable comme application native
---
Catégories couvertes
Catégorie	Exemples d'articles
🔩 Serrurerie / Métallerie	Ferme-portes, cylindres, serrures, garde-corps, anti-panique…
🪟 Vitrerie / Miroiterie	Double vitrage, verre feuilleté, miroirs, parcloses…
🌅 Occultations	Volets roulants, stores, brise-soleil, rideaux, persiennes…
🚪 Menuiseries Extérieures	Fenêtres bois/PVC/alu, portes-fenêtres, châssis, coulissants…
🏗️ Généralités	Échafaudages, nacelles, protections, main d'œuvre…
---
Sources (22 marchés publics)
`Bonneuil` `Bussy-Saint-Georges` `CD93` `Champigny` `CPAM` `Eragny` `Fontenay` `Gagny` `IDF Construction Durable` `Ivry` `Lagny-sur-Marne` `Livry-Gargan` `Nogent-sur-Marne` `Noisy-le-Grand` `Pantin` `Puteaux` `Sevran` `Thiais` `UPEC` `Vaujours` `Villiers-le-Bel` `Yerres`
---
Architecture technique
```
Application web statique (HTML + JavaScript)
├── Aucun serveur requis
├── Aucune base de données externe
├── Données embarquées dans index.html
└── Fonctionne 100% côté client (navigateur)
```
Paramètre	Valeur
Hébergement	GitHub Pages
Protection	Mot de passe hashé SHA-256
Stockage externe	Aucune donnée transmise
Mise à jour	Remplacement du fichier `index.html`
---
📲 Installation (PWA)
L'application est accessible à :
🌐 https://kurusano.github.io/biblio-prix-crm/
Pour l'installer comme une application native :
iPhone : Safari → Partager → Sur l'écran d'accueil
Android : Chrome → Menu → Ajouter à l'écran d'accueil
PC (Edge) : Menu → Plus d'outils → Épingler à la barre des tâches
---
👤 Auteur
Djibril Ndiaye — Apprenti Chargé d'Affaires BTP  
CESI École d'Ingénieurs, Nanterre
Projet réalisé dans le cadre d'un mémoire CESI :  
« Améliorer la réactivité et la précision du chiffrage des marchés publics dans une PME de second œuvre »
---
CRM — Conception Réalisation de Menuiseries, Courtry (77)
