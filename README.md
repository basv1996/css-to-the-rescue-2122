# CSS to the Rescue @cmda-minor-web 2021 - 2022

## Inhoudsopgave

- [Week 1](#week-1)
- [Week 2](#week-2)
- [Week 3](#week-3)
- [Week 4](#week-4)
- [Bronnen](#bronnen)


### Het eindresultaat

![Screenshot van de kubus](https://raw.githubusercontent.com/basv1996/css-to-the-rescue-2122/main/docs/img/wiki_img/eindresultaat.png)


#### live link
- [Link naar het eindresultaat](https://basv1996.github.io/css-to-the-rescue-2122/eindopdracht/)

### Opdracht

- **Gekozen opdracht**: Rubik's Cube
- **Grootste uitdaging**: Alles werkend krijgen met alleen CSS

### Nieuwe Technieken

- Custom Properties
- Transform/Animation
- Calc
- Flexbox
- Grid
- Checkbox interaction


## Week 1

![Screenshot van week 1](https://github.com/basv1996/css-to-the-rescue-2122/blob/main/docs/img/wiki_img/Schets_kubus_layout_week1.png?raw=true)

In week 1 heb ik 1 kubus gemaakt die in het midden van de pagina stond. Dit waren 6 list items en deze moest ik positioneren dat de 6 vlakken een kubus vormde. 
Nadat Dit was gelukt heb ik hulp gevraagd over het positioneren van de kubussen er omheen. Hierbij heb ik hulp gekregen en heb ik 26 blokjes om de middelste kubus heen gebouwd.

Ik heb verschillende tips gekregen van Sanne voor het maken van de kubus:

* Eerst Roteren daarna translate
* Je hebt 3x een transform nodig
* 1 Voor de hoeken
* 1 voor de middenstukken
* 1 voor het midden midden
* Custom Properties zijn je beste vriend 


### Schetsen

Aangezien ik niet een heel goed idee had hoe ik moest beginnen aan deze opdracht heb ik een schets gemaakt hoe ik mijn HTML wil gaan opbouwen. Om het semantisch correct te  houden heb ik ervoor gekozen om list items te gebruiken voor m'n kubus blokken.

![Eerste afbeelding met schetsen](https://raw.githubusercontent.com/basv1996/css-to-the-rescue-2122/main/docs/img/wiki_img/Schets_week1.jpg)
![Tweede afbeelding met schetsen](https://raw.githubusercontent.com/basv1996/css-to-the-rescue-2122/main/docs/img/wiki_img/Schets2_week1.jpg)


### Wat ging goed

- Het is gelukt om 1 kleine kubus te maken
- voor het eerst 3d animatie gemaakt

### Waar had ik moeite mee

- Om na te gaan hoe de zijkanten van een kubus geplaatst moeten worden in 3D


### Mislukte plannen

- De blokken te animeren en te draaien op een hover, hier ga ik volegnde week mij meer in verdiepen.


## Week 2

![Screenshot van week 2](https://raw.githubusercontent.com/basv1996/css-to-the-rescue-2122/main/docs/img/wiki_img/Schets_kubus_layout_week2.png)

In week 2 ben ik verder gegaan met de animatie. Hierbij heb ik checkboxxen gebruik om hier interactie met de kubus op uit te oefenen. Ook is het gelukt om een layer van de kubus een kwartslag te draaien. Dit werkt nog niet helemaal smooth. Alle blokken aan de bovenkant draaien tegelijkertijd waardoor dit een heel raar effect met zich mee geeft. Hier moet ik nog naar kijken hoe ik dit kan verhelpen.

Ik kwam er achter om de blokjes uit op de makkelijke manier te selecteren ik wel 27 blokjes nodig had in plaats van 26. Hierdoor kon ik m'n code gaan herschrijven.

![schets van blokjes genummerd](https://raw.githubusercontent.com/basv1996/css-to-the-rescue-2122/main/docs/img/wiki_img/Schets_kubus_layout.png)


### Wat ging goed

- Het is gelukt de animatie werkend te krijgen
- Het is gelukt om alle blokjes goed neer te zetten


### Waar had ik moeite mee

- de juiste blokjes te selecteren om 1 kant van de kubus te laten draaien
- Als 1 kant draait dan draaien alle blokjes indivdueel


### Mislukte plannen

- 1 zijkant laten draaien

## Vakantie

Niks gedaan


## Week 3

### Dag 1
![Kubus animation week 3](https://raw.githubusercontent.com/basv1996/css-to-the-rescue-2122/main/docs/img/wiki_img/Kubus-animation-week3.gif)

### Dag 2
![Kubus animation week 3](https://raw.githubusercontent.com/basv1996/css-to-the-rescue-2122/main/docs/img/wiki_img/KubusWeek3_dag2.gif)



Het is de week na de vakantie week 3. Ik ben weer verder gegaan met de kubus. Aangezien ik voor de vakantie vast liep met het draaien van een zijvlak heb ik mijn code gerefactord. Hierbij heb ik de kubus opnieuw opgedeeld in lagen. Hierbij heb ik ervoor gezorgd dat bijvoorbeeld alle nummers van de tafel van 3 aan de rechterkant van de kubus zitten.


### Wat ging goed

- Door het refactoren van de code kan ik nu ook de zijkant draaien


### Waar had ik moeite mee

- Het opnieuw schrijven van de code
- Nieuwe dingen te bedenken om toe te voegen aan de kubus
- een afbeelding op 1 van de zijdes van de kubus te krijgen
- de afbeelding goed mee te laten draaien als een zijde van de kubus draait


### Mislukte plannen

- De afbeelding mee te laten roteren met de kubus
- grid toe te voegen voor de pijlen rond om de kubus heen

## Week 4

week 4 is aangebroken en het zijn de laatste lootjes voor de eindoplevering. Ik heb wat extra thema's toegevoegd aan de kubus en mijn code gerefactord. 

![Screenshot van de kubus](https://raw.githubusercontent.com/basv1996/css-to-the-rescue-2122/main/docs/img/wiki_img/eindresultaat.png)

### Wat ging goed

- Het refactoren van de code
- thema's toevoegen aan de kubus


### Waar had ik moeite mee

- geen moeite ergens mee gehad, ik begrijp de technieken


### Mislukte plannen

- Lasershow te laten werken alleen als de rotate aan staat.



## Credits
* Huilsessies
* [Sanne 't Hooft](https://github.com/shooft)
* [Pepijn](https://github.com/ppijn)

## Bronnen

- [nth of child generator](https://css-tricks.com/examples/nth-child-tester/)
- [css grid genrator](https://cssgrid-generator.netlify.app/)
- [Intro to 3D transforms](https://3dtransforms.desandro.com/cube)
- [coding a 3D pure css cube](https://dev.to/ziratsu/coding-a-3d-cube-in-pure-css-52gg)
- [codepen van Sanne](https://codepen.io/shooft)

