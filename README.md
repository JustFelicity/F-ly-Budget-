# Fély Budget — PWA simplifiée

Cette version conserve les fonctionnalités de Fély Budget avec une interface plus épurée : textes plus grands, moins de descriptions secondaires, boutons plus faciles à toucher et navigation toujours limitée à quatre onglets.

## Fonctions conservées
- Budget quotidien indépendant, solde disponible et objectif d'épargne facultatif.
- Dépenses multiples dans les quatre catégories : transport aller, transport retour, repas et autres dépenses.
- Ajout, modification et suppression des dépenses.
- Clôture de journée avec affectation séparée de l'objectif et du surplus dans les enveloppes choisies.
- Enveloppes personnalisées, dépôts, retraits et transferts internes.
- Calendrier et consultation des journées enregistrées.
- Suppression complète d'une journée avec annulation des dépôts issus de sa clôture et recalcul des soldes.
- Statistiques sur les 7 derniers jours, le mois en cours ou toute la période.
- Export et restauration d'une sauvegarde JSON.
- Fonctionnement hors connexion après le premier chargement complet depuis une adresse HTTPS.

## Mise à jour de l'application déjà installée
1. Décompresser cette archive.
2. Remplacer les fichiers du dépôt GitHub Pages par le contenu du dossier `fely-budget-pwa`.
3. Publier les changements.
4. Ouvrir Fély Budget avec Internet et recharger la page une fois pour recevoir la nouvelle version.
5. Les données locales sont conservées si l'adresse (domaine et chemin) reste identique et si les données du site n'ont pas été effacées.

Le service worker utilise un nouveau nom de cache (`fely-budget-pwa-v4`) afin de remplacer les anciens fichiers mis en cache.

## Installation
La PWA doit être hébergée en HTTPS. Ouvrir son adresse dans Chrome sur Android, attendre le chargement complet, puis choisir dans le menu ⋮ « Installer l'application » ou « Ajouter à l'écran d'accueil ».

## Données et confidentialité
Aucun compte, serveur, abonnement ou service distant n'est requis pour les fonctions de l'application. Les données restent dans le stockage local du navigateur sur cet appareil. Effacer les données du site ou changer d'adresse peut les supprimer ou rendre les anciennes données inaccessibles : exporter régulièrement une sauvegarde JSON.
