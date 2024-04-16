# IframeJellySeerr
Iframe jellySeerr in JellyFin

Add @import url('https://cdn.jsdelivr.net/gh/matthijsvrenswoude/IframeJellySeerr/jellyseerr-update.css'); in Jellyseer docker volume to the beginning of any css file in app -> .next -> static -> css

Add @import url('https://cdn.jsdelivr.net/gh/matthijsvrenswoude/IframeJellySeerr/jellyfin-expansion.css'); to Jellyfin dashboard -> admin settings -> General -> Custom CSS

Download and build https://github.com/jellyfin/jellyfin-web except with the following file overwrites:

- home.html -> src/controllers/home.html
- home.js -> src/controllers/home.js

Remove all contents from C:\Program Files\Jellyfin\Server\jellyfin-web and move over everything from github jellyfin-web newly created dist folder

Optional: 
Add @import url("https://cdn.jsdelivr.net/npm/jellyskin@latest/dist/main.css"); to Jellyfin Dashboard -> General -> Custom CSS
