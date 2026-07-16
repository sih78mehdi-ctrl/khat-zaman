# خط الزمن — تاريخ الجزائر (1827-1971)

Application web installable (PWA) pour réviser les dates importantes de l'histoire de l'Algérie.

## Contenu de ce dossier

```
index.html        → l'application (page principale)
manifest.json      → fichier qui rend l'app "installable"
sw.js               → service worker (fait fonctionner l'app hors-ligne après la 1ère visite)
icons/              → toutes les icônes (générées à partir de votre logo 4AM)
```

## Mettre en ligne sur GitHub Pages

1. Créez un nouveau dépôt (repository) sur GitHub, par exemple `khat-zaman`.
2. Mettez **tous les fichiers de ce dossier** (`index.html`, `manifest.json`, `sw.js`, et le dossier `icons/`) **à la racine** du dépôt — ne les mettez pas dans un sous-dossier.
3. Sur GitHub : `Settings` → `Pages` → dans "Build and deployment", choisissez `Deploy from a branch`, branche `main`, dossier `/ (root)` → `Save`.
4. Après 1-2 minutes, votre app sera disponible à :
   `https://VOTRE-NOM-UTILISATEUR.github.io/khat-zaman/`

## Installer l'app sur téléphone/PC

Une fois le lien ouvert :
- **Android (Chrome)** : menu ⋮ → "Ajouter à l'écran d'accueil" / "Installer l'application".
- **iPhone (Safari)** : bouton Partager → "Sur l'écran d'accueil".
- **PC (Chrome/Edge)** : une icône d'installation ⊕ apparaît dans la barre d'adresse.

L'icône affichée sera votre logo 4AM (fourni), et l'app fonctionnera même sans connexion après la première ouverture.

## Ce qui a été modifié dans cette version

- **Fusion et suppression des doublons** : toutes les dates de vos 3 pages ont été regroupées ; chaque date n'apparaît qu'une seule fois (47 dates au total, de 1827 à 1971).
- **Découpage en 5 tranches chronologiques** : les 47 dates sont réparties (10 / 10 / 9 / 9 / 9) en 5 périodes, dans l'ordre chronologique.
- **6 rubriques de jeu** : les 5 tranches, chacune jouable séparément, + une 6ᵉ rubrique "المراجعة الشاملة" qui contient la totalité des 47 dates — pour que l'enfant révise tranche par tranche puis fasse une révision générale.
- **Jeu de tri supprimé** : il ne reste que le "خط الزمني" (frise), "اربط التاريخ بالحدث" (association) et "اختبار" (quiz).
- **Correction visuelle** : sur la frise, les points de couleur (vert/jaune/etc.) ne recouvrent plus le texte de la date — la mise en page a été refaite pour garantir un espacement fixe entre le point et le texte.
- **Application installable (PWA)** : ajout de `manifest.json`, `sw.js` et des icônes aux formats nécessaires, avec votre logo 4AM comme icône de l'application.
