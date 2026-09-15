# ALTEZ Dagplanning - GitHub Pages testversie

Deze versie draait volledig statisch op GitHub Pages, zonder Node.js of externe database.

## Wat werkt
- kantoorplanning met 5 weken
- planning toevoegen, wijzigen, verwijderen en verslepen
- dashboard en historiek
- mobiele werfapp
- vrachten afvinken als geleverd / gemonteerd
- problemen melden
- projectcontext uitlezen wanneer de office-pagina als Trimble Connect projectextensie draait

## Belangrijke testbeperking
De data staat in `localStorage` van de browser. Daardoor delen twee tabbladen op dezelfde browser de data, maar een pc en gsm delen de data nog niet. Voor echte live synchronisatie tussen toestellen is later een kleine online database/API nodig.

## Publiceren
1. Maak GitHub repository `Altez_Dagplanning`.
2. Upload de volledige inhoud van deze map naar de root van de repository.
3. GitHub > Settings > Pages.
4. Deploy from a branch > `main` > `/ (root)`.
5. Open `https://jonasvanhecke-98.github.io/Altez_Dagplanning/`.

## Trimble Connect
Manifest URL:
`https://jonasvanhecke-98.github.io/Altez_Dagplanning/manifest.json`

Office URL:
`https://jonasvanhecke-98.github.io/Altez_Dagplanning/office/`

Werfapp:
`https://jonasvanhecke-98.github.io/Altez_Dagplanning/field/`
