# 🎨 Pinceau de Guerre

**Peignez votre armée. Chaque bataille devient un tableau.**

Un jeu de stratégie où l'on dessine ses troupes au pinceau, où l'on trace ses sorts en plein combat, et où chaque affrontement laisse une œuvre unique sur le champ de bataille. Tout tient dans un seul fichier HTML : aucune installation, aucune dépendance.

---

## ✨ Ce qui le rend unique

* **🖼️ Le tableau de bataille :** les morts éclaboussent le terrain de peinture et les armées y laissent des coups de pinceau. À la fin de chaque vague, la bataille devient un tableau nommé et signé (« Requiem en Azur, n°12 »), à enregistrer ou à partager. Vos œuvres rejoignent votre galerie.
* **🔥 Les sorts peints :** en combat, tracez au pinceau un trait de feu, de l'encre gelée ou une aquarelle de soin. Ils consomment de l'encre, regagnée avec le temps et à chaque ennemi vaincu.
* **⏸ La pause tactique :** figez la bataille et peignez vos sorts à tête reposée.
* **📐 Des ennemis qui changent de forme :** phalange, coin, croissant, pinces, trois blocs, échelon. Adaptez votre formation avant l'assaut.
* **🧭 Des cartes à lire :** chaque vague a son terrain, des cratères jusqu'à un vrai labyrinthe. Les armées contournent les obstacles, et les pointillés rouges annoncent la route probable de l'ennemi.
* **🗺️ Un terrain qui grandit :** l'arène et l'armée s'agrandissent au fil des vagues, et la caméra dézoome pour en montrer l'ampleur.
* **🥁 Des tambours de guerre :** une musique générée en direct, lente en préparation et martiale au combat.
* **💾 Une partie sauvegardée :** reprenez où vous en étiez, et gardez votre record.

---

## 🗺️ Le terrain

| Obstacle | Unités | Flèches | Orbes des Mages |
|---|---|---|---|
| **Mur** | Bloquées | Bloquées | Passent au-dessus |
| **Trou** | Bloquées | Passent | Passent |
| **Marais** | Ralenties | Passent | Passent |

| Vague | Carte | L'enjeu |
|---|---|---|
| 1 et 2 | La Plaine | Aucun obstacle |
| 3 | Les Cratères | Les trous divisent les armées, mais pas les tirs |
| 4 | Le Marais | Traverser ralentit, contourner rallonge |
| 5 | Les Deux Cols | Un mur, deux passages |
| 6 | La Forêt de Piliers | Les rangs se brisent et les tirs sont coupés |
| 7 | La Faille | Deux ponts seulement |
| 8 | Le Serpent | Un long couloir en lacets |
| 9 | Le Bastion | Une forteresse ennemie à deux portes |
| 10 | Le Dédale | Un vrai labyrinthe, différent à chaque passage |

Les cartes reviennent ensuite dans le même ordre, à partir de la vague 11.

---

## ⌨️ Commandes sur ordinateur

| Action | Commande |
|---|---|
| Peindre des unités | Clic gauche maintenu dans la zone de déploiement |
| Gommer / rembourser | Clic droit maintenu |
| Choisir une unité | Touches 1 à 5 |
| Lancer la vague | Espace |
| Choisir un sort en combat | Touches 1, 2, 3, puis tracer au clic gauche |
| Ranger le sort | Échap, ou nouvel appui sur le sort |
| Pause tactique | Espace ou P |
| Zoomer / dézoomer | Molette, touches + et - |
| Déplacer la vue | Clic gauche hors de la zone (partout en combat), clic molette, flèches, WASD ou ZQSD |
| Recadrer automatiquement | F ou bouton AUTO |
| Arbre de compétences | U |
| Couper le son | M |

Le repli reste un choix explicite : il se fait uniquement avec le bouton **Repli**.

---

## 📱 Commandes sur téléphone

| Action | Geste |
|---|---|
| Peindre ou gommer | Un doigt dans la zone de déploiement, selon le bouton Peindre / Gommer |
| Tracer un sort | Choisir le sort, puis tracer avec un doigt |
| Déplacer la vue | Un doigt ailleurs, ou partout en combat s'il n'y a pas de sort choisi |
| Déplacer et zoomer | Deux doigts, partout |
| Recadrer | Bouton AUTO |

Le jeu se joue en portrait comme en paysage, mais le paysage offre un meilleur champ de vision.

---

## 🚀 Lancer le jeu

**Sur ordinateur :** double-cliquez sur `index.html`. Un navigateur peut bloquer la sauvegarde pour un fichier local : le jeu reste jouable, mais la partie n'est alors pas conservée.

**Sur téléphone, avec votre PC :** lancez un petit serveur dans le dossier du jeu, puis ouvrez `http://ADRESSE-IP-DU-PC:8000` depuis le même réseau Wi-Fi.

```bash
python -m http.server 8000
```

**En ligne :** déposez `index.html` sur n'importe quel hébergeur de pages statiques.

---

## 🛠️ Sous le capot

* **Rendu :** WebGL2 instancié pour les unités, avec repli automatique sur Canvas 2D. La peinture vit sur son propre canevas, déplacé par le GPU.
* **Simulation :** tableaux typés (Structure of Arrays), grille spatiale, séparation des unités par relaxation bornée pour éviter les téléportations.
* **Son :** entièrement synthétisé avec la Web Audio API, sans aucun fichier.
* **Stockage :** partie, galerie et record dans le `localStorage` du navigateur.
