# Victor Olin
Roll: Projektledare

## Projektarbete
Jag har jobbat med Valter på Churf's runtime library. Vi har tillsammans utvecklat
heap-klassen i biblioteket som erbjuder minneshantering och garbage collection.
Vi har tillsammans spenderat många timmar på analys, debugging och gemensamt
arbete.

Utöver heap-klassen som är kärnan av runtime biblioteket så har jag även utvecklat
en profiler som är ett verktyg som används för att testa garbage collectorn så att
den markerar rätt objekt, friar rätt mängd minne och tar tid på vissa delar av programmet
för att kunna mäta prestandan av biblioteket.

Jag har även utvecklat ett FFI för biblioteket. Eftersom det är jobbigt att hantera
kompilerade C++ klassnamn i LLVM IR så utvecklade jag ett FFI för att kunna anropa
C++ funktioner genom att kalla på top-level C-style funktioner. Detta underlättade
integrationen av biblioteket med resten av kompilatorn.

## Rapport
På rapporten har jag jobbat mycket med teori och implementation av mitt och Valters
arbete, men också skrivit på lite mer generella delar i mån av tid.
På rapporten har jag skrivit:
- Abstract + Sammandrag
- Samtliga delar av Introduktion
- Samtliga delar av 2.3 (Runtime)
- Paragrafer 4.0 till och med 4.3 (Runtime Environment)
- Resultat om garbage collectorn, 5.2 (Demonstration)
- Delar av 6.3 (Discussion)
- Majoriteten av 7 (Conclusion)

Sammanlagt cirka 11 utav 49 sidor

## Övrigt
För övrigt har jag skrivit projektdagboken varje vecka.