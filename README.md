# Introduksjon til React - en workshop

Dette er en workshop for deg som vil lære React, eller som vil få en litt mer strukturert introduksjon til dette rammeverket.

Workshopen er **ikke ferdig enda**, men tar sikte på å ferdigstilles innen sommeren 2019. 

## Oppgaver
Vi skal lage den neste SoMe-hypen: Bekkstagram! 

Hver oppgave har en lenke til en CodeSandbox der du kan implementere oppgaven. Oppgaven er løst når testene under "Tests"-fanen blir grønne. Du kan også gå inn på filen "SOLUTION.md" i hver CodeSandbox for å få løsningen (om du skulle sitte fast).

### Del 1: React 101 - De grunnleggende byggesteinene!

#### Oppgave 1: Hei verden!
La oss starte med basics. Få React til å skrive ut en `<h1 />`-tag med teksten "Bekkstagram" inni.

https://codesandbox.io/s/64xvkjl7k3

#### Oppgave 2: Din første komponent!
Lag en ny komponent, Header, som skriver ut en `<h1 />`-tag med teksten "Bekkstagram" inni, og bruk den i appen din.

https://codesandbox.io/s/nwlvzqzm3p

#### Oppgave 3: Bilde-komponent
Komponenter er morsommere når man bruker props. Lag en ny komponent `Image` som tar i mot to props, `src` og `alt`, og som lager en `<img />`-tag som bruker disse to propsa.

Legg også på css-klassen `image` på `<img />`-taggen, så får den tilogmed riktig design!

https://codesandbox.io/s/8njr15z4x8

#### Oppgave 4: En liste med bilder
Det beste med komponenter er at man kan bruke dem gang på gang. I denne oppgaven skal du loope ut en liste med bilder. Listen finner du i code-sandboxen.

Husk at du trenger en unik `key` for hvert element i lista - ellers vet ikke React hvilket element som endrer seg!

https://codesandbox.io/s/w0n3nr56ww

#### Oppgave 5: Sett sammen komponenter med children
På tide å gjøre innleggene våre litt mer innholdsrike. I denne oppgaven skal vi lage tre nye komponenter, og sende inn data ved hjelp av en ny prop - `children`. 

https://codesandbox.io/s/myxn92wm6x

#### Oppgave 6: Vis ett og ett bilde
Alle de kule appene har forskjellige sider og URLer. Det burde vi også få oss. I denne oppgaven skal vi bruke biblioteket `react-router` til å lage to forskjellige sider i applikasjonen vår - `FeedPage` og `DetailPage`.

Begynn med å ta en titt på [dokumentasjonen til React Router](https://reacttraining.com/react-router/web/guides/quick-start) for en rask introduksjon til de forskjellige funksjonene du finner der.

https://codesandbox.io/s/l77qzql7z9

### Del 2: Tilstand og sideeffekter

#### Oppgave 7: Legg til likes som lokal state på hvert bilde
La oss gjøre Bekkstagram litt mer avhengighetsskapende ved å introdusere muligheten til å like et bilde. Antall likes et bilde har kan ses på som en tilstand, og dette er en perfekt anledning til å bruke hooks. 

https://codesandbox.io/s/2xojz42rnn

#### TODO

### Del 3: Avansert React

#### TODO

### Del 4: Bonusoppgaver

Har du kommet deg helt hit er du åpenbart en kløpper i React allerede. Kjempebra jobba! 

Her har du et par ekstraoppgaver du kan bryne deg på om du kommer helt i mål

#### TODO

## Løsningsforslag

Står du fast? Løsningsforslag til hver oppgave ligger i hver CodeSandbox-link i filen `SOLUTION.md`. Her står det også litt nøyere beskrevet hva man skal gjøre og hvorfor. Det anbefales å ta en titt på hvert av disse når du er ferdig, om ikke annet bare for å få forklart at du hadde helt rett.
