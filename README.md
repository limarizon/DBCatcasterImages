# Database images

Mapje per team → in een gemeenschappelijke github (verantwoordelijke team 3)

Verschillende features :

- Helderheden van het scherm **percentage (veelvoud van 25%)** 
- Verschillende apparaten (gsm X per team aanduiden settings vasthouden) 
- Dichtbij en ver (aantal percent pixels van scherm in foto → ruwweg) 
- Afstand (in cm) 
- Hoeveel kleuren op het scherm 
- Welke kleuren op het scherm **RGB formaat (R,G,B) met waarden tussen 0 en 255 (na elkaar van links naar rechts op het scherm)**
- Lichtinval (0 geen licht, 1 artificieel licht, 2 natuurlijk licht)
- Lichtreflectie op het scherm (1 lichtreflectie of 0 geen lichtreflectie)
- Scherm (laptop/smartphone/tv…) → nummer per scherm settings vasthouden
- Unieke identifier (integer die uniek is binnen map)

 

In .jpg formaat 

 
Scherm geplaatst in het midden (ongeveer) 
Zeker middelste 5x5 pixels voor analyse
If 2 colors: Op x-as itereren tot de 2 kleuren gevonden zijn vertrekkende van de 5x5 in het midden.

Voorbeeld bestandsnaam: 25_5_70_100_2_255_255_0_100_100_100_1_1_3_2333.jpg
--> helderheid van het scherm op de foto is 25%, gsm 5 van dit team, 70% van de pixels van de foto zijn pixels van het scherm, de afstand tussen het scherm en de camera is 100cm, er zijn 2 kleuren te zien op het scherm, de eerste kleur (van links naar rechts) is de kleur met RGB waarden 255,255,0, de tweede kleur heeft RGB waarden 100,100,100, er is artificieel licht, er is lichtreflectie op het scherm, de foto is van scherm 3 van dit team en de identifier van deze foto is 2333. 
