# 🎨 Pinceau de Guerre

**Peignez votre armée. Chaque bataille devient un tableau.**

Un jeu de stratégie où l'on dessine ses troupes au pinceau, où l'on trace ses sorts en plein combat, et où chaque affrontement laisse une œuvre unique sur le champ de bataille. Tout tient dans un seul fichier HTML : aucune installation, aucune dépendance.

---

## ✨ Ce qui le rend unique

* **📈 De 5 unités à des milliers :** on commence sans armée, avec juste de quoi recruter 5 Fantassins, sur un terrain minuscule et vu de très près. Vague après vague, l'armée, le terrain et la vue grandissent jusqu'à des batailles titanesques.
* **🤝 Le mode Duo :** un joueur est le Général et peint son armée, l'autre est le Titan, une unité géante avec son propre arbre d'évolution. Se joue sur le même écran ou en ligne.
* **🖼️ Le tableau de bataille :** les morts éclaboussent le terrain de peinture et les armées y laissent des coups de pinceau. À la fin de chaque vague, la bataille devient un tableau nommé et signé (« Requiem en Azur, n°12 »), à enregistrer ou à partager. Vos œuvres rejoignent votre galerie.
* **🔥 Les sorts peints :** en combat, tracez au pinceau un trait de feu, de l'encre gelée ou une aquarelle de soin. Ils se débloquent et se renforcent dans la branche **Grimoire de guerre** de l'arbre de compétences : à vous de choisir entre une armée plus forte et des sorts plus puissants. Ils consomment une encre rare, qui se regagne lentement avec le temps et un peu à chaque ennemi vaincu. Chaque touche de peinture agit sur les unités les plus proches de son centre et s'épuise à mesure qu'elle les touche : un sort entame les premiers rangs, il ne traverse pas toute une armée. Le Feu et le Givre ne touchent que les ennemis, tandis que le Soin soigne tous vos alliés, Titan compris.
* **⏸ La pause tactique :** figez la bataille et peignez vos sorts à tête reposée.
* **⚖️ Des effets de zone qui s'épuisent :** l'orbe du Mage, le rayon et l'Onde de Choc du Titan, comme les sorts, frappent d'abord les ennemis les plus proches, puis s'arrêtent. On use l'ennemi rang après rang.
* **📐 Des ennemis qui changent de forme :** phalange, coin, croissant, pinces, trois blocs, échelon. Adaptez votre formation avant l'assaut.
* **🧭 Des cartes à lire :** chaque vague a son terrain, des cratères jusqu'à un vrai labyrinthe. Les armées contournent les obstacles, et les pointillés rouges annoncent la route probable de l'ennemi.
* **🗺️ Un terrain qui grandit :** l'arène et l'armée s'agrandissent au fil des vagues, et la caméra dézoome pour en montrer l'ampleur.
* **🥁 Des tambours de guerre :** une musique générée en direct, lente en préparation et martiale au combat.
* **💾 Une partie sauvegardée :** reprenez où vous en étiez, et gardez votre record.

---

## ⚔️ Les unités

| Unité | Prix | Rôle |
|---|---|---|
| Fantassin | 2 Or | Mêlée, nombreux et bon marché |
| Archer | 6 Or | Tir à distance, derrière les Tanks |
| Tank | 18 Or | Bouclier de première ligne |
| Assassin | 45 Or | Flanqueur rapide aux coups critiques, à débloquer |
| Mage AoE | 250 Or | Artillerie d'élite, à débloquer : chaque orbe frappe les 6 ennemis les plus proches de l'impact |

L'arbre de compétences compte maintenant cinq branches sur quatre paliers, avec des compétences profondes pour les grandes guerres : Formation Serrée, Dernier Rempart, Soif de Sang, Vétérans, Volée, Archimage, Conscription et Pigments Denses.

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

## 🗿 Le mode Duo : Général et Titan

Le **Général** joue comme en solo : il peint son armée, lance les vagues et trace ses sorts. Le **Titan** ne dirige qu'une seule unité, immense. Il enjambe murs et trous, frappe automatiquement ce qui l'entoure, et dépense ses **Âmes** pour évoluer. En duo, les vagues ennemies grossissent jusqu'à atteindre 3,2 fois leur taille en solo. Les ennemis en plus ne rapportent pas d'or au Général : ils nourrissent le Titan.

Son arbre est une constellation à cinq branches. Chaque compétence le fait grandir et ajoute une partie visible à son corps, ce qui permet de le repérer même très dézoomé.

| Branche | Ce qu'elle apporte | Capacité |
|---|---|---|
| ❤️ Le Cœur | PV, régénération, carapace, vol de vie, peau qui résiste aux tirs, Seconde Vie | — |
| 👊 Les Poings | Dégâts, coups en arc, frénésie, coups qui brisent les rangs | **J** Onde de Choc |
| 👁️ Le Regard | Rayon plus long et plus perçant, faisceaux multiples, chasse aux élites, pétrification | **K** Regard Ardent |
| 🦶 Les Jambes | Vitesse, piétinement, pas sismique, ruée, taille de Colosse | **L** Charge |
| 👑 La Couronne | Aura qui renforce, soigne et protège l'armée, Terreur, Tribut en or | **I** Cri de Ralliement |

Le Titan grandit au rythme des ennemis : ses PV et ses dégâts suivent la vague, pour qu'il puisse rester au corps à corps. Son rayon ne traverse plus tout : chaque faisceau brûle les 3 premiers ennemis sur sa ligne, puis s'arrête.

**Sur le même écran :** le Général utilise la souris. Le Titan utilise ZQSD (WASD en QWERTY), J K L I pour ses capacités, et T pour son arbre. Sur tablette, le Titan a un joystick à l'écran.

**En ligne :** le Général choisit « Créer une salle » et obtient un code de 4 caractères (par exemple `K7QF`). Le Titan choisit « Rejoindre avec un code », tape ce code, et la partie démarre. Le Général peut aussi partager un lien direct qui remplit le code tout seul. Le service gratuit PeerJS sert seulement d'annuaire pour le code. Ensuite, les deux navigateurs se connectent directement l'un à l'autre, et chacun voit l'adresse IP de l'autre. Certains réseaux (4G, réseaux d'entreprise) bloquent ces connexions directes. Il faudrait alors un serveur relais, qui n'est pas encore en place. En ligne, le Titan se déplace aussi à la souris ou au joystick.

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
