# jimogit.github.io

Portfolio de Jean-Marc Aoun, publié par GitHub Pages : https://jimogit.github.io/

Une seule adresse pour trois projets :

- `index.html` : la barre commune et le projet « IA en santé », écrit en dur (accueil et six onglets) ;
- `projets/replai.html`, `projets/fanunit.html` : ReplAI stats et Fanunit, chargés au premier affichage puis gardés en mémoire ;
- `fanunit.html`, `replai.html` : pages de renvoi, pour les anciens liens et pour garder une carte de partage propre à chaque projet.

Ancres : `#sante/<onglet>`, `#replai/<chapitre>`, `#fanunit/<chapitre>`. Les anciens liens (`/#besoin`, `fanunit.html#resultats`…) restent valides.

Site statique, sans outil de construction. Polices auto-hébergées dans `fonts/` (licences OFL jointes), images dans `img/`.

Pour tester en local, servir le dossier (`python3 -m http.server`, puis http://localhost:8000/) : ouvert directement depuis le disque, le navigateur refuse de charger les fragments de `projets/`.
