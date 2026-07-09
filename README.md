# Kuray Infinite Fusion Multiplayer — Docker Compose

1. `docker compose up`
2. `docker stop fusion_server`
3. Place the Full KIF Folder with multiplayer files inside the `app/` folder.
   *The server expects `server.rb` at `/app/KIFM/server.rb`.*
4. `docker start fusion_server`

Players connect to:

YOUR_SERVER_IP:12975

## Folder layout

```text
app/
 └── KIFM/
      └── server.rb

