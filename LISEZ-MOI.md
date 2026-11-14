# Mon Cabinet — mise à jour du 13 novembre 2026 (soir)

## Ce qu'il faut déposer sur GitHub

```
index.html              remplace l'ancien
sw.js                   remplace l'ancien
manifest.webmanifest    remplace l'ancien
polices/                NOUVEAU DOSSIER à ajouter
    lora.ttf
    lora-italique.ttf
icones/                 inchangé
```

Puis ouvrir l'application en wifi et **recharger deux fois**.

## Protection des données — le correctif

Un défaut faisait que chaque onglet gardait sa propre copie des
rendez-vous et réécrivait tout le stockage. Un onglet ouvert depuis
plusieurs heures pouvait ainsi effacer le travail fait ailleurs.

Trois protections :

- **Les onglets se synchronisent.** Dès qu'un onglet enregistre,
  les autres se mettent à jour dans la seconde.
- **L'écriture fusionne.** Avant chaque enregistrement, l'application
  relit ce qui est stocké et ajoute au lieu de remplacer. Les
  suppressions volontaires sont respectées.
- **Historique automatique.** Les dix derniers états sont conservés.
  Onglet *Réglages*, section **Revenir en arrière** : chaque état
  porte sa date, son heure et son nombre de rendez-vous.

Un bandeau avertit désormais quand l'agenda est ouvert dans plusieurs
onglets à la fois.

L'enregistrement est aussi forcé dès que l'application passe en
arrière-plan, au lieu d'attendre.

## Le reste de la mise à jour

- fond doré, étoiles, titre du jour en or brossé
- barre d'onglets dorée sur toute la largeur
- cartes cernées d'un filet doré, écriture bleu nuit
- police Lora embarquée (aucun accès internet)
- répertoire proposé dès les premières lettres, remplit téléphone et profil
- glissement du doigt entre onglets ; en haut de la Journée, change de jour
- onglet retenu au rechargement, retour à Journée après fermeture complète
- plus de zoom au double-tap, plus de rebond élastique

## Conseil

Fermer les onglets en trop sur la tablette, et n'ouvrir l'agenda que
depuis un seul endroit.
