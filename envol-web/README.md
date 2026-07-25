# L'Envol des Savoirs — Version Web

Application éducative pour enfants de 2 à 10 ans (20 jeux, profils, niveaux, cœurs, musique, bilan). Une seule page HTML, prête à déployer sur Vercel.

## 1. Mettre le projet sur GitHub

Dans un terminal, à l'intérieur de ce dossier :

```bash
git init
git add .
git commit -m "L'Envol des Savoirs - première version"
```

Puis sur https://github.com :
1. Crée un nouveau repository (ex: `envol-des-savoirs`), vide, sans README.
2. Copie les commandes qu'il te donne, du type :

```bash
git remote add origin https://github.com/TON-PSEUDO/envol-des-savoirs.git
git branch -M main
git push -u origin main
```

## 2. Déployer sur Vercel

1. Va sur https://vercel.com et connecte-toi avec ton compte GitHub.
2. Clique **Add New > Project**.
3. Sélectionne le repository `envol-des-savoirs`.
4. Vercel détecte que c'est un site statique — aucune configuration nécessaire.
5. Clique **Deploy**.

En moins d'une minute, l'app est en ligne sur une URL du type :
`https://envol-des-savoirs.vercel.app`

## 3. Mises à jour futures

Chaque fois que tu modifies `index.html` :

```bash
git add .
git commit -m "Description du changement"
git push
```

Vercel redéploie automatiquement à chaque push.

## Notes importantes

- La progression de chaque enfant est sauvegardée via le stockage intégré du navigateur (par profil/prénom). Elle reste donc liée à l'appareil utilisé.
- La musique de fond démarre uniquement après un clic sur le bouton 🔈 (règle de sécurité des navigateurs contre le son automatique).
- La photo de l'auteur est intégrée directement dans le fichier (pas d'image externe à héberger séparément).
