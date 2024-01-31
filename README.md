# mintvibe.github.io

# problemer 

Når skjermen er liten, og menyen vises som en drop down, må man bruke "long press" for å få frem menypunktene på Safari. Dette er kanskje fordi "hover" fungerer ulikt på Safari og andre nettlesere?

Det tok lang tid å få ting til å se bra ut i ulike nettlesere på desktop og mobil. Jeg har forsøkt å løse problemet med ulik skjermstørrelse med Media queries For eksempel slik, vises lenker når det er plass, men en drop-down når sjermen blir for liten. 

Det er fortsatt litt problemer med safari på IOS og MAC enheter.

```css
@media (min-width: 661px) {
    .links {
        display: inline-block;
    }
    
    .container .dropdown {
        display: none;
    }

    .content .image img {
        width: 100%; /* Make the image fill its container on even smaller screens */
        margin-right: none; /*remove margin-right on smaller screens */
    }
}
```

# Refrence sheet til It prosjekt: Void energy drink

Jeg brukte Canva.com for å lage logo til siden min, jeg tok en av pre sets de hadde og byttet logo navn til "void"
Canva.com «Brukt for å lage logoen»

# Alle bildene brukt på nettsiden min er laget av Ai på pixlr.com (Ai genererte bilder for «Void Energy Drink») noen exempler
<img width="452" alt="image" src="https://github.com/MintVibe/mintvibe.github.io/assets/82243184/d64cfc32-c643-45f7-8174-7662177c2db9">
<img width="452" alt="image" src="https://github.com/MintVibe/mintvibe.github.io/assets/82243184/4967e34f-945a-4f64-84e4-d0a345a18d4e">

# Jeg brukte -cdnjs font awsome, for fonts + Google fonts
https://fonts.google.com/specimen/Poppins

# Inspirasjon til å lage en reklame "ad" til et selskap kom etter jeg så en video av noen som lage en reklame for Noen nike sko, hvis du ser video ser du at hoved siden ser lik ut, siden jeg syntes sytling så nydelig ut, her er videon
Insiprasjon video https://www.youtube.com/watch?v=HD7604Amqz0&t=8s&ab_channel=ProCoder

# Animasjon, dette er koden jeg brukte for å få teksten til å bli animert når du refresher siden
-Sliding animations https://github.com/michalsnik/aos

# Små detaljer jeg brukte en del tid på

Når skjermen blir mindre eller på (mobil) forsvinner navbaren og blir byttet ut mot en ny dropdown meny i form av (bar-icon).


Nav baren har farge basert på hvem side på nettsiden du er, eks når du er home så er home delen av navbaren farget lilla.

I footer har jeg link til instagram, jeg brukte lit tid på å lage en Instagram bruker til dette prosjekte, her finner du Instabrukeren: https://www.instagram.com/voidenergyvgs/

Gallay har en fin hover effekt som lager en lilla skygge og gjør bilde lit større 

Logo, Hvis du trykker på logoen blir du send tilbake til home

Nesten alt på siden er "trykkbart"


