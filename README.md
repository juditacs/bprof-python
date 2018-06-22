# BProf Python felkészítő

## Jupyter telepítése

[Hivatalos dokumentációs](http://jupyter.org/install)

### Két lehetőség

**FIGYELEM** mindenképp Python3-as verziót telepítsetek.

1. Anaconda telepítése: nagy Python disztribúció + csomagkezelő
2. telepítés pip-pel: beépített Python csomagkezelő

    pip install jupyter

## Jupyter használata

A Jupyter egy ún. notebook szervert futtat a háttérben. Legegyszerűbben a

    jupyter notebook

paranccsal tudjuk elindítani tetszőleges terminálból.

Ez a parancs elindít egy webszervert és megnyit egy fájl listázó böngészőtabot
az alapértelmezett böngészőben. Bármely más böngészőt is használhatunk, de az
autentikációhoz szükségünk lesz a tokent tartalmazó url-re, amit a terminálból
ki lehet másolni, egy ilyet kell keresni:

    http://localhost:8888/?token=<token>

A Windows 10 nem oldja fel a `localhostot`, át kell írni `0.0.0.0`-ra.
