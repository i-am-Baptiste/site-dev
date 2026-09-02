# Association Queimada — site web

Site vitrine statique (HTML/CSS/JS, sans dépendances) pour l'Association Ludique Queimada
(jeux de plateau, Magic: The Gathering, Altered) à Montigny-le-Bretonneux.

## Développement local

Aucun build nécessaire. Ouvrez `index.html` dans un navigateur, ou servez le dossier :

```bash
python3 -m http.server 8000
```

Puis visitez `http://localhost:8000`.

## Structure

- `index.html` — page unique avec sections Accueil / Activités / Adhésion / Contact
- `style.css` — styles (palette claire inspirée du logo du club)
- `app.js` — menu mobile et petites interactions
- `assets/logo.png` — logo de l'association

