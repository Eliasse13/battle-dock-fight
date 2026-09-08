# Battle Dock Fight

Jeu de combat 2D jouable au navigateur, sur le port de Marseille.
Vanilla HTML/CSS/JS, aucune dépendance à installer.

- `index.html` — accueil, vestiaire de personnalisation, tirage de billet (poste), pièces et coffres à butin.
- `jeu.html` — moteur de combat : combos nommés, effets, mode carrière, deux joueurs sur le même écran, en ligne par code de salon.

## Jouer
Ouvrir `index.html`, créer son docker au vestiaire, tirer un billet, descendre sur le quai.

## Commandes
Déplacement `◀ ▶` / flèches · Sauter `▲` · Sec `J` · Lourd `K` · Garde `↓` · Rage `L`
Joueur 2 au clavier : `Q D Z S` + `F G H`

## En ligne
Le multijoueur utilise Supabase Realtime (diffusion, aucune table). Remplacer `SB_URL` et `SB_KEY` en haut du script de `jeu.html` par les valeurs du projet Supabase de ton choix.
