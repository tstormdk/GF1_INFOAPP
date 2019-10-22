# BageOpskrift til at løse APP-Opgaven
### Dette er ikke den komplette løsning

__Start med at planlægge din app, herunder__
* Tegn nogle wireframes
* Lav dit "design"
  * Skrifttyper
  * Farver
  * Billeder
  * Diagrammer fra illustrator med data
* Lav dit ikon der skal være på din telefon, når app'en installeres
  * 512 X 512 pixels
  * 912 x 192 pixels

__Opret en mappe til din app__
* læg den et sted du ved hvor du kan finde den
* opret undermapper som:
  * images
  * css
  * icons
  * etc
* flyt dine optimerede billeder over i mappen

__Editor klargøring__

Eller find dit framework, start dine html og css filer op.
Start din editor - Brackets, Visual Studio Code eller den du har valgt.
* Åben din mappe i din editor
* opret din index.html fil
* opret en manifest.json fil (Skal bruges senere)

__Template tid__

Find den template du vil bruge.
Ret den til i den online version du har adgang til først
>Når du er tilfreds.
>Og du skal til at sætte billeder ind.

>__Så er det tid at kopiere din kode og sætte den ind i din egen index.html__

__Billeder og stier__

Du skal nu til at sætte dine billeder ind.
Du skal sørge for det passer med stierne.
Dette er en sti
```
/images/graph_smoking.svg
```
det samme gælder for skrifttyper og eksterne stylesheets

_psst. de ligger i \<head\>_

__manifest.json__

Et andet sted der skal rettes til er i manifest.json filen
Hent den fra sitet her eller copy/paste koden fra eksemplet her på siden.
Her skal der også rettes til.
```
"src": "/images/icons-192.png",
      "type": "image/png",
```
Skal eksempelvis måske ændres til:
```
"src": "/icons/icons-192.png",
      "type": "image/png",
```

Og alle steder markeret med

__#Ændres__

Skal ændres til det rigtige.

__\<head\>__

Nu skal du copy/paste koden med meta tags fra siden her
Den hjælper med at gøre din html side til en app :iphone:
_Hvis du læser tags'ene så kan du næste se hvad de hjælper med_

__netlify - DROP __

Så kan det betale sig at oprette en konto hos Netlify
Det er her vi skal lægge vores mappe med alle vores filer op.
Så får vi en www adresse vi kan bruge til at oprette en QR-kode på
Og
Oprette en genvej på vores telefon.
