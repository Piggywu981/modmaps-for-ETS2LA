# data.zip for JTSLA

Install by rename and replace data.zip in app/Plugins/Map
## IMPORTANT: REPLACE "lane_offsets.json" in "app/Plugins/Map/utils" for accurate lane offsets!!!

Generated with https://github.com/JimJokes/maps/tree/modSupport on wsl Ubuntu

Commands:
```
npx parser -g "/mnt/e/SteamLibrary/steamapps/common/Euro Truck Simulator 2" -m "/mnt/c/Users/piggy/Documents/Euro Truck Simulator 2/mod" -o "/home/piggy/maps/datajp"
npx generator graph -m europe -i "/home/piggy/maps/datajp" -o "/home/piggy/maps/datajp" #Essential, won't work without graph.json
```
---
v2025.3.23 Integrated by PiggyWu981
