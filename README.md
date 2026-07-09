# Kuray Infinite Fusion Multiplayer — Docker Compose 

1. `docker compose up`
2. `docker stop fusion_server`
3. Place Full KIF Folder with multiplayer files inside `app/` folder.
The server expects `server.rb` at `/app/KIFM/server.rb`.
4. `docker start fusion_server`

## Folder layout

app/
  └── KIFM/
        └── server.rb

Players connect to:

YOUR_SERVER_IP:12975
