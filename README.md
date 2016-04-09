# Robolot 2016
**Ponència 'Imagina Snap i Arduino'**

Properament s'obrirà un espai on els Serveis d'Innovació i Formació i el CESIRE publicaran tota la informació relacionada amb el projecte: documentació, fitxers de treball i exemples, agenda d'activitats, equip de suport... També es publicitarà aquí aquest espai definitiu.

Publiquem aquí la informació bàsica per a poder començar a treballar amb les eines presentades a la ponència.

  - El projecte [Snap!](http://snap.berkeley.edu/) ens serveix de referència. Trobareu informació i també podreu treballar amb [Snap! en línia](http://snap.berkeley.edu/snapsource/snap.html).
  - Al Citilab trobareu [Snap4Arduino](http://s4a.cat/snap/), amb exemples i explicacions, i amb les [descàrregues](http://s4a.cat/snap/#download) pels diferents sistemes operatius.
  - Amb aquestes eines ja podeu començar a treballar la majoria de idees presentades.
  - Només ens faltarien el *firmware* específic per ampliar les funcionalitats disponibles a Snap! En molts projectes no necessiteu realitzar aquest pas.

  ##Firmware ImaginaFirmata
  
  - Trobareu una versió *beta (0.5)* per poder treballar [aquí](https://github.com/jguille2/SA5/files/211052/robolot16.zip).
  - Dins el *zip* hi ha una carpeta *firmware* on teniu els fitxers que necessiteu per programar la placa amb la IDE d'Arduino i ampliar el *StandardFirmata*. Com aquest *firmware* afegeix llibreries específiques, haureu de colocar la carpeta *libraries* al lloc corresponent (més informació del treball amb llibreries [aquí](http://www.arduino.cc/en/Guide/Libraries)).
  - Amb el *firmware* carregat podeu utilitzar la placa amb tots els casos generals (utilitzar Snap4Arduino normalment). Per utilitzar les funcionalitats ampliades teniu dos exemples a la carpeta *SnapFiles*. Amb l'arxiu *blocks_nun-tone-pulses-ping.xml* carregareu a Snap4Arduino tots els blocs genèrics i a *blocks_imagina.xml* s'afegiran a més a més uns blocs adaptats a la placa Imagina-Arduino.
  
