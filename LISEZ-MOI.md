# Mon Cabinet — installation sur la tablette

## Ce que contient ce dossier

```
index.html              l'application
manifest.webmanifest    nom, icône, mode plein écran
sw.js                   le fichier qui permet de fonctionner sans internet
icones/
    icone-192.png
    icone-512.png
    icone-maskable-512.png
    icone-180.png
```

Garder exactement cette structure : les trois premiers fichiers à la racine,
les images dans un dossier nommé `icones`.

## Mettre en ligne

1. Créer un compte sur github.com si ce n'est pas déjà fait.
2. Créer un dépôt (*New repository*), par exemple `mon-cabinet`, en **public**.
3. Déposer les fichiers : *Add file* → *Upload files*, glisser l'ensemble,
   puis *Commit changes*.
4. Ouvrir *Settings* → *Pages*, choisir la branche `main` et le dossier `/ (root)`,
   puis *Save*.
5. Patienter une minute. L'adresse apparaît en haut de la page, de la forme
   `https://votre-nom.github.io/mon-cabinet/`

## Installer sur la tablette

1. Se connecter au wifi, ouvrir cette adresse dans Chrome.
2. Menu (les trois points) → *Ajouter à l'écran d'accueil* ou *Installer l'application*.
3. L'icône dorée apparaît sur l'écran d'accueil.

À partir de là, l'application fonctionne **sans internet**.

## Mettre à jour

Remplacer `index.html` sur GitHub, puis ouvrir l'application une fois en wifi.
Elle se rafraîchit toute seule.

## Les données

Tout est enregistré **dans la tablette uniquement**. Rien ne part ailleurs,
rien ne se synchronise avec un autre appareil.

Vider les données de Chrome ou désinstaller l'application **efface tout**.

→ Utiliser régulièrement *Enregistrer une sauvegarde*, en bas de l'application,
et conserver le fichier ailleurs (Drive, mail, clé USB).
Le bouton *Restaurer une sauvegarde* permet de tout remettre en place.

## Rappel du fonctionnement

- **Journée** : grille fixe de 5h30 à 14h30 par créneaux de 45 min, puis heures
  rondes l'après-midi (cliquer sur l'heure pour la modifier, ou sur « temps
  ouvert » pour y écrire une note). Glisser du doigt pour changer de jour.
- **Dimanche** : pas de rendez-vous, uniquement les formations et les stages.
- **Personnes** : répertoire alimenté automatiquement, historique, fiche technique.
- **Pense-bête** : notes libres.
- **Réglages** : la liste des protocoles proposés après chaque séance.
