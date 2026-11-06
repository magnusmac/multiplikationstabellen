# Gångertabellen

Ett fristående övningsverktyg för multiplikationstabellen 1–10. Allt ligger i `index.html` – ingen server, ingen installation, inga externa resurser. Fungerar offline i Chrome på Chromebook.

Valda tabeller sparas och följer med mellan Öva, Spel och Kalkylblad.

## Delar

**Dagens pass** – cirka 10 minuter (högst 30 frågor) som anpassas efter eleven.
- 55 faktapar; 3 × 7 och 7 × 3 räknas som samma men frågas åt båda hållen.
- Fyra lådor: *Ny*, *Övas*, *Nästan*, *Sitter*. Ett faktum sitter efter snabbt rätt svar (cirka 3 s) två olika dagar. Sitter-fakta repeteras med växande intervall (3, 6, 12 … dagar).
- Nya fakta i strategiordning: 1, 2, 10, 5 → 4, 8, 3 → 9 och kvadrattal → 6 → 7 → 6×6, 6×7, 6×8, 7×7, 7×8, 8×8. Högst två nya per pass, och bara när det mesta går bra.
- Ett nytt faktum visas först med strategi, skrivs sedan ur minnet och kommer tillbaka efter 2 och 5 frågor. Ungefär var fjärde fråga är ett svagt faktum, resten är sådant eleven kan.
- Fel frågas igen efter 2 och 5 frågor. Är felet ett grannfaktum (54 för 7 × 8) övas även grannen.
- Första gången: ett startprov med 20 frågor utan synlig tid.

**Strategier** – sex korta moduler med ett rutnät som eleven ändrar själv, följt av fyra uppgifter med strategin som stöd:
*Vrid* (kommutativitet), *Dubbelt* (2, 3, 4, 8), *Halva tian* (5), *Tian minus en* (9), *Kvadrat och granne* (6×6, 7×7, 8×8 och grannarna), *Dela upp* (6, 7).
En modul låser upp nya fakta ur sin familj i Dagens pass. Under Dagens pass kan spärren stängas av med *Öppna alla tabeller*. Fakta eleven redan kan påverkas inte, och 1:an och 10:an är alltid öppna.

**Min karta** – 10 × 10-karta där varje ruta visar sin låda med färg och siffra. Veckan jämförs bara med förra veckan (pass, frågor, andel rätt, nya som sitter).

**Visa för läraren** – en sammanfattning som eleven visar eller skriver ut: lådor och karta, startprov, strategier, inställningar, veckan jämfört med förra, och saker att titta närmare på (långsamma svar på lätta fakta, andel rätt under 80 %, inga pass, nästa faktum som väntar på en strategi). Namnet som skrivs in sparas inte, och inget skickas någonstans.

**Visning och ljud** – uppläsning av uppgifterna (webbläsarens talsyntes, svenska), större text och knappar, och rutnätsstöd vid varje fråga.

**Så funkar det** – kapitel för föräldrar och lärare: hur passet går till, lådorna, strategierna, ordningen, tips för hemmet, var data sparas och vanliga frågor.

**Öva** – blandade frågor med direkt återkoppling. Multiplikation, division eller båda; 10/20 frågor, hela tabellen eller 60 sekunder. Klockan är dold som standard.
- Vid fel visas rätt svar och eleven skriver det en gång till innan nästa fråga.
- Vid andra felet på samma faktum visas en strategi i ett rutnät (t.ex. 7 × 8 = 7 × 7 + 7).
- Svarstiden mäts tyst per faktum och sparas lokalt, som grund för ett adaptivt pass.
- Resultat med lista över fel och *Öva på felen*.

**Spel**
- *Bubblor* – tryck på rätt svar innan bubblan flyger iväg. Inga liv: en missad fråga kommer tillbaka. 20 frågor.
- *Para ihop* – memory med uträkning och svar.
- *Kapplöpning* – svara rätt för att springa ifrån snigeln, katten eller haren. Vid fel skrivs rätt svar av.
- *Bingo* – markera svaret på brickan, fyll en rad.
- *Sant eller falskt* – så många du hinner på en minut (tangenter S/F).
- *Rektanglar* – bygg alla rektanglar (högst 10 × 10) med ett visst antal rutor. Tränar faktorpar och rutnätsbilden.
- *Kodlåset* – hitta den saknade faktorn i tre ledtrådar för att öppna låset. Kopplar till division.
- *Fyra i rad* – två klämmor på 1–9: flytta en, markera produkten, först till fyra i rad mot datorn (lätt eller klurig).

**Kalkylblad** – skapa utskrivbara blad: multiplikation, division, saknad faktor, blandat, tom tabell eller *Titta, täck, skriv, jämför* (20 rader per blad, eleven viker undan svaren och rättar själv). 20/40/60 uppgifter, facit på egen sida. Skriv ut eller välj ”Spara som PDF”.

**Tabellen** – interaktiv 10 × 10-tabell. Hoppräkna steg för steg i en tabell, eller tryck på en ruta för att se en strategi.

## Data

Ingen elevdata lämnar datorn. Framsteg, inställningar, rekord och svarstider sparas bara lokalt i webbläsaren. Varje elev bör därför logga in på Chromebooken med sitt eget konto.

## Använda

Öppna `index.html` i webbläsaren, eller lägg filen i Google Drive och dela den. Den kan också publiceras via GitHub Pages.
