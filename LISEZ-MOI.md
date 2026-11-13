# Mon Cabinet — mise à jour du 13 novembre 2026

## Ce qu'il faut déposer sur GitHub

```
index.html              l'application (remplace l'ancien)
sw.js                   mise en cache hors ligne (remplace l'ancien)
manifest.webmanifest    nom, icône, couleurs (remplace l'ancien)
polices/                NOUVEAU DOSSIER — à ajouter
    lora.ttf
    lora-italique.ttf
icones/                 inchangé, rien à refaire
```

**Le dossier `polices` est nouveau.** Sans lui, l'application s'affiche
avec les polices du système : elle marche, mais perd son allure.

## Après le dépôt

Ouvrir l'application en wifi et **recharger deux fois**. Le cache change
de version, donc le premier rechargement installe la nouvelle, le second
l'affiche.

## Ce qui change

- fond doré avec étoiles scintillantes, titre du jour en or brossé
- barre d'onglets dorée sur toute la largeur
- cartes de rendez-vous cernées d'un filet doré, écriture bleu nuit
- police Lora, embarquée dans le dossier (aucun accès internet)
- en créant un rendez-vous, le répertoire est proposé dès les premières
  lettres du prénom ou du nom, et remplit téléphone et profil
- glissement du doigt entre les onglets ; dans la Journée en haut de page,
  le glissement change toujours de jour
- l'onglet en cours est retenu au rechargement, et revient sur Journée
  après une fermeture complète
- plus de zoom au double-tap, plus de rebond élastique

## Les données

Inchangées. Elles vivent dans le navigateur de la tablette et ne sont pas
touchées par la mise à jour. Penser à faire une sauvegarde de temps en
temps avec le bouton en bas de page.
