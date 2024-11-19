# Case3-JavaScript

### Case Modul 3 - Grundläggande JavaScript

Din uppgift är att skapa en applikation som dynamiskt kan hantera en lista med länkar. 
Här är ett exempel på en länksamling:

Länksamling
- [Aftonbladet](http://aftonbladet.se)
- [Expressen](http://expressen.se)
- [Dagens nyheter](http://dn.se)

Du ska skapa funktionalitet om gör det möjligt att dynamiskt skapa en lista av länkar enligt exemplet 'Länksamling' ovan. Din kod ska innehålla ett formulär med lämpliga formulärfält. En användare ska kunna använda formuläret för att skapa klickbara länkar.
Struktur och innehåll i länklistan ska baseras på html elementen ul, li och a. Den som använder applikationen ska förstå hur man gör för att skapa nya länkar. Det kan ske med ikoner, knappar, grafik, information etc - ett designat gränssnitt. 

Vi vill att du strävar efter följande namngivningsprinciper:
- använd latinska tecken för variabelnamn och funktioner
- använd förklarande namn, namngivna camelCase
- skriv kommentarer i din kod
- avsluta instruktioner med semikolon ;
- skriv kod med indrag (indentation)

Applikationen får inte använda externa ramverk, utan det är *vanilla* JavaScript och CSS som gäller.

Dela upp struktur, innehåll, design och logik. 

### Starta ditt arbete
Skapa ett privat repo på GitHub och koppla det till din lokala utvecklingsmiljö (Visual Studio Code).
Under projektet - senast 27 november bjuder du in dina lärare. Se Settings -> Manage access -> Add people

Lägg till

andsju (Anders)

frozenbanana (Henry)

addkolon [Mattias]

***

### Grundläggande krav

Applikationen ska
- visa en tom länklistan när sidan läses in
- innehålla minst en media query (baseras på sidans bredd) som hanterar vy för mobil och skärm
- inte skapa ett listelement om det inte finns en url eller länktext angiven

En användare ska kunna
- lägga till en länk
- ta bort en länk
- markera en länk (ex visuellt ange favoritlänk)

Din kod ska 
- använda externa filer för CSS och JavaScript
- validera innehållet i ett formulär med kod som du själv skapar baserat på datatypen **string**. 
(Dvs - om du validerar ett fält i ett formulär med ett attribut ska det även finnas en egen validering)  

Utvecklingen av applikationen ska finnas dokumenterad på GitHub. Du ska ha gjort minst 10 commits under perioden du arbetar med projektet.

***

### Utmaningar
(Förutom att applikationen uppfyller de grundläggande kraven ovan) 

Här finns följande utmaningar. Anta en eller flera!

En användare ska kunna
- redigera en länk 
- flytta en länk upp eller ned i listan
- använd en array för att lägga till länkar i samband med att sidan laddas in, ex initialt fylla en tom lista med några länkar
- designa sidan så att den som besöker sidan ser vilken kategori av länkar som är tanken (film, musik, historia...) 


***

### Inlämning och redovisning
Redovisning av caset är den 11 december.

Förbered er på att redovisa applikationen på ca 5 minuter. Då visar ni (demonstrerar) er applikation genom att dela skärm.
Vi ränkar med att redovisningen startar kl 9:00.

*Förbered 5 minuters redovisning enligt följande mall:*

#### I reovisningen ska du:
- demonstrera applikationen
- - visa hur man lägger till, markerar och tar bort en länk
- - visa exempel på annan funktionalitet (ex ngn av utmaningarna)
- berätta vad du är mest nöjd med (design, kod, struktur...)
- berätta vad du skulle vilja att applikationen kan göra, men inte hunnit att koda

Redovisningen sker i bokstavordning (efternamn A-Ö)

### Handledning
Det kommer finnas möjlighet till handledning fram tills den 10 december. I första hand är det under vanlig lektionstid.

Lycka till!
