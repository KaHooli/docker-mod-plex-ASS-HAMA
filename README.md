# Absolute Series Scanner (ASS) & HTTP Anidb Metadata Agent (HAMA) - Docker mod for Plex

This mod adds these plugins to Plex, to be downloaded/updated during container start.

More information, see
 - [Absolute Series Scanner (ASS)](https://github.com/ZeroQI/Absolute-Series-Scanner)
 - [HTTP Anidb Metadata Agent (HAMA)](https://github.com/ZeroQI/Hama.bundle)

In plex docker arguments, set an environment variable `DOCKER_MODS=ghcr.io/kahooli/plex-ass-hama`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=ghcr.io/kahooli/plex-ass-hama|linuxserver/mods:plex-mod2`
