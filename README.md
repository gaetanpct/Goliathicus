# Goliathicus

Jeu de stratégie en ligne pour 2 à 4 joueurs, inspiré du Stratego, dans un royaume de fantasy.

## Lancer en local
    npm install
    npm start
puis ouvrir http://localhost:3000

## Déployer sur Render
- Type : Web Service
- Build Command : npm install
- Start Command : npm start
- La variable PORT est fournie par Render.

## Structure
- server.js : serveur Express et Socket.io (salons, minuteurs, IA de remplacement)
- public/game : règles partagées (pièces, plateaux, moteur, IA)
- public/js et public/style.css : interface
