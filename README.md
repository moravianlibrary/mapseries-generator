# mapseries-generator
Generator of GeoJSON for mapseries with regular grid in defined coordinates

Idea:
Nastroj na online vytvoreni mapoveho indexu (pro pozdejsi kalalogizovani):

Verze 1:
1) Tabulkove zadani souradnic - ktere vytvori pravidelnou mrizku.

Inline image 1
Zápis 163850 odpovídá souřadnicím 16°38´50"
a la http://www.staremapy.cz/marc/

EPSG.io : vyber souradnocoveho systemu - api documentation at https://github.com/klokantech/epsg.io

For transforming more points: https://github.com/klokantech/epsg.io/issues/47 do 4326

Idealne: Closure Tools - https://github.com/klokan/closure-library-plovr-hello-world-skeletons
s OL3.

Grid: http://dekajp.github.io/demos/index.html

2) Vybrani poli, ktere do mrizky nepatri

3) Ocislovani

4) (Doplneni o title)

5) Export do GeoJSON + TopoJSON (vystup pro do stringu v JavaScriptu) (link na: http://geojson.io?data-url )

Documentation for expected format: http://mapseries.georeferencer.org/jk/doc/navod.docx 

Povinna metadata:
·       SHEET, v němž je uloženo číslo mapového listu
·       TITLE, v němž je uložen název mapového listu
Sample data on Dropbox.

https://www.dropbox.com/sh/re4tk91jofgpcw2/AACdCfGD2dMh4-RhRmX2gUWva?dl=0
