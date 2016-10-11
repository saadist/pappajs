# PappaJS

## Föreberedelse

1. Skapa en ny mapp.
2. Kopiera **pappa.html** till mappen.
3. Skapa en ny fil **barn.js** i mappen.

Testa skriv följande instruktioner i **barn.js** och öppna **pappa.html** i en webläsare:

    rubrik("Denna text sätts en gång vid start.");

    function upprepa()
    {
        cirkel(100, 100, 50)
    }

## Instruktioner

Instruktioner du skriver i function upprepa() { ... } utförs om och om igen, ungefär 30 gånger i sekunden. De andra intruktionerna utförs en gång precis i början.

Funktioner för att rita:

    sudda();
    penna("color");
    punkt(x,y);
    rektangel(x,y, bredd, höjd);
    cirkel(x,y, radie);
    linje(x,y, x,y);
    linjer([x,y, x,y, x,y, ..., x,y]);
    rubrik("text");
    text(x,y, "text");

Andra funktioner:

    startaom();
    pausa();
    fullscreen();
    fraga("text");

Variabler:

    frame
    mus.x
    mus.y
    tid.h
    tid.m
    tid.s
    tid.ms

