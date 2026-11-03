# MAFIA NIGHT – första spelbara versionen

En mobilanpassad multiplayer-webbapp för Maffia utan spelledare.

## Starta

1. Installera Node.js 18 eller senare.
2. Kör `npm install` i projektmappen.
3. Kör `npm start`.
4. Öppna `http://localhost:3000`. För andra telefoner behöver servern vara tillgänglig på samma nätverk via datorns lokala IP-adress, eller publicerad på en HTTPS-host med stöd för Node.js och WebSockets.

## Innehåll

- Rumskoder, privata roller, spelare på egna telefoner.
- Valfritt antal maffia, polis, doktor och självmordsbombare (inom spelarantalets gränser).
- Automatisk natt, diskussion, röstning och vinstkontroll.
- Anonym eller öppen röstning.
- Självmordsbombaren aktiveras endast när den röstas ut och får välja en annan spelare.

## Viktiga begränsningar

Detta är en första testversion, inte en produktionsklar app. Spelrum lagras endast i serverns minne och försvinner vid omstart. Spelare kan inte återansluta efter att sidan laddats om eller anslutningen brutits. Inga konton, databaser, modereringsverktyg eller automatiska tester finns ännu. Servern behöver driftsättas för spel mellan olika nätverk. Polisens undersökningssvar visas privat på polisens telefon. Vid lika röstetal elimineras ingen.
