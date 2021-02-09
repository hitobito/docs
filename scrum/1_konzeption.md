# Konzeption

## Definition of Ready

* Story hat einen sprechenden Titel und ist mit dem Modulnamen prefixed. z.B. MESSAGES: SMS via Abo senden
* Die Story kann nicht mehr weiter in Teil-Features zerlegt werden

## Referenz-Stories

### Feature

#### Titel

PEOPLE: Heimatplanet soll auf Person hinterlegt werden können

#### Beschreibung

Neben der Adresse soll neu auch der Heimatplanet auf der Person hinterlegt werden können.

Folgende Optionen stehen zur Auswahl:

* Erde (Standard)
* Mars
* Venus
* Melmac

Weitere Planeten können pro Instanz hinzugefügt werden. #4242

#### Mockup

hier folgt ein Mockup ...

#### Techspec

Tabelle 'people':
- home_planet, neu, belongs_to

Tabelle 'home_planets':
- has_many: people
- name, string
- population, bigint

### Tech

#### Titel

TECH: Flux Capacitor Gem updaten

#### Beschreibung

Aktuelle in Version 42.1, update auf 42.2.

Dies behebt eine kritische Lücke im Zeitreisemodul
