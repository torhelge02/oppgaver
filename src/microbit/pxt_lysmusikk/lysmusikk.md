---
title: "PXT: Lysmusikk"
author: Helene Isnes
language: nb
---


# Introduksjon {.intro}

I denne oppgaven skal vi få micro:biten til å spille ulike toner avhengig av hvor mye lys som treffer micro:biten sin lyssensor. Dette kan du bruke til å lage musikk!

Vi trenger litt ekstra utstyr:
- 2 ledninger med krokodilleklemmer
- 1 buzzer (liten, sort høytaler) eller hodetelefoner


# Steg 1: Lysnivå {.activity}

*Micro:biten har en lyssensor som måler lysstyrke. Lysstyrken blir oppgitt som et tall mellom 0 (mørkt) og 255 (lyst), og lagres i klossen `lysnivå` som du finner i kategorien `Inndata`.*

## Sjekkliste {.check}

- [ ] Lag en variabel som heter "lysnivå" (`Variabler` -> `Lag en variabel` -> skriv inn: lysnivå) og bruk en `sett variabel til`-kloss for å lagre målt lysstyrke i den. 

	![Bilde hvor variabelen lysnivå blir satt til lysnivå (fra sensor)](sett_til_lysnivaa.png)


# Steg 2: Musikk {.activity}

## Sjekkliste {.check}

- [ ] Lag koden som er vist under. ![Bilde som viser klossen spill tone Middle C i 1 takt](spill_tone_kloss.png) -klossen finner du i kategorien `Musikk`. Legg merke til at du skal bytte fra 1 til 1/2 takt. 

	![Bilde som viser en hvis-ellers kloss med åpne plasser til spill tone klosser](hvis_ellers.png)

- [ ] Kopier `spill tone ...`-klossen ved å høyreklikke på den og velg `Lag kopi`. Du endrer tonen ved å klikke på den.

- [ ] Fyll resten av de ledige plassene i `hvis-ellers`-klossen med klosser som spiller tonene Middle D, Middle E, Middle F, Middle G og Middle A.

## {.tip}

For å få flere plasser i `hvis-ellers`-klossen, trykk på pluss-tegnet (+) som står helt nederst på klossen.

# Steg 3: Velg når tonene skal spilles av {.activity}

## Sjekkliste {.check}

- [ ] Velg selv om du skal spille av toner hele tiden (`gjenta for alltid`), hver gang du trykker på en knapp, når du rister micro:biten eller lignende. Finn passende kloss og legg resten av koden inn i den.


# Steg 4: Gjør klart til lyd {.activity}

*Micro:biten har ikke høytalere. Derfor må vi koble til en buzzer eller hodetelefoner. Måten vi kobler til en buzzer er litt forskjellig fra måten vi kobler til hodetelefoner. Først kommer en sjekkliste for hvordan du kobler til en buzzer, og etter det kommer sjekklisten for om du bruker hodetelefoner.*

## Buzzer sjekkliste {.check}

- [ ] Fest en ledning fra der det står 0 på micro:biten til pinnen som det står pluss (+) ved på buzzeren. 

- [ ] Fest den andre ledningen fra der det står GND på micro:biten til den andre pinnen (-) på buzzeren.

## Hodetelefoner sjekkliste {.check}

- [ ] Fest en ledning fra der det står GND på micro:biten til helt øverst på den metalliske delen av hodetelefonene.

- [ ] Fest den andre ledningen fra der det står 0 på micro:biten til helt nederst på den metalliske delen av hodetelefonene. 

- [ ] Simulatoren viser hvordan det nå skal se ut:

	![Bilde av hvordan man kobler til hodetelefoner](tilkobling_lyd.png)

## Test prosjektet {.flag}

- [ ] Last ned programmet til micro:biten. 

- [ ] Kjør programmet. Prøv å endre lysnivået ved å skygge for med hånden. 

## {.tip}

Hvis du ikke hører alle tonene kan du justere tallene i `hvis-ellers`-klossen. 


## Utfordringer {.challenge}

- [ ] Prøv å spille tonene lengre eller kortere enn i en 1/2 takt

- [ ] Utvid `hvis-ellers`-klossen og legg til flere toner for flere lysnivåer. 
