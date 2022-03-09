## Table of contents:

[Week 1](https://github.com/ROEL2407/City_menu#week-1)</br>
[Week 2](https://github.com/ROEL2407/City_menu#week-2)</br>
[Week 3](https://github.com/ROEL2407/City_menu#week-3)</br>
[Week 4](https://github.com/ROEL2407/City_menu#week-4)</br>

### Week 1

<strong>Dag 1</strong></br>
Vandaag ben ik begonnen met het project van CSS to the rescue. Hier heb ik voor de case gekozen van de menu kaart. Als eerste wilde ik writing mode verkennen. Hier heb ik nog niet eerder mee gewerkt en het lijkt mij in sommige gevallen erg handig om te weten.

![writing mode van boven naar beneden in plaats van links naar rechts](https://github.com/ROEL2407/css-to-the-rescue-2122/blob/main/wiki_images/writing%20mode.PNG)

<strong>Dag 2</strong></br>
Op vrijdag had ik genoeg tijd tussen mijn gesprekjes om aan CSS to the rescue te gaan. Hiervoor ben ik bezig geweest met grid. Dit ging mij gemakkelijk af omdat ik flexbox al erg ken en grid in mijn ogen het er redelijk op lijkt.

hierna ben ik met een shadow begonnen die ik op de grid items wil. Ik wil namelijk het laten lijken alsof ze 3D van het scherm afkomen met behulp van deze shadow.

Allereerst ben ik begonnen met een normale box-shadow. Hierbij kwam ik erachter dat ook aan de zijkanten van de shadow, een gradient komt en niet een rechte afkapping:

![Box shadow](https://github.com/ROEL2407/css-to-the-rescue-2122/blob/main/wiki_images/box-shadow.PNG)

Hierna ben ik verder gaan zoeken naar een oplossing die leek op wat ik wilde verwerkelijken. Een mede student die naast mij zat was bezig met zijn opdracht toen ik zag dat hij een voorbeeld had. Daarin zat precies de shadow die ik dacht nodig te hebben. Ik heb deze link gevraagd en heb vervolgens dit uitgeprobeerd. Dit had kunnen werken maar omdat mijn blokken waar ik de shadow op wilde te groot waren, werd de shadow zo groot dat deze in een andere shadow ging lopen. 

Uiteindelijk ben ik gekomen bij clip paths. Dit had ik nog niet eerder gebruikt dus ik ben hier aardig lang mee bezig geweest om de vorm te krijgen. Hier wil ik later dan weer een gradient van maken.

### Week 2

<strong>Dag 3</strong></br>
Vandaag ben ik verder gegaan met de shadow op de grid items. Na een beetje stuntelen van welk type gradient ik moest gebruiken, welke kleuren en wanneer de gradient moest over gaan op elkaar kwam ik op de volgende uitkomst waar ik erg tevreden mee ben:

![](https://github.com/ROEL2407/css-to-the-rescue-2122/blob/main/wiki_images/building.PNG)

Hierdoor kreeg ik gelijk inspiratie. Het lijkt nu alsof de blokken wolkenkrabbers zijn. Hiermee kwam ik op het idee om een weg tussen de "gebouwen" te leggen en met een interactie een autootje te laten rijden. hiervoor heb ik de achtergrond van de main nog even aangepast om dit op een weg te laten lijken

Het autootje heb ik dan ook gelijk gemaakt. Deze wilde ik in eerste instantie  met 1div en een before en after. Hier kwam ik al snel achter dat ik niet precies wist hoe ik dit kon fixen. Om latere problemen te voorkomen heb ik nu het verdeeld waar de lichten en de wielen in divs zitten.

<img src="https://github.com/ROEL2407/City_menu/blob/main/wiki_images/auto.png">

<strong>Dag 4</strong></br>
Vandaag ben ik begonnen met de interactie en animatie van het menu. Ik wilde graag dat op basis van een checkbox die aangevinkt is of niet, het autootje te laten rijden. Hiervoor heb ik een checkbox met een label erbij gemaakt zodat er op de label geklikt kan worden waarna de auto gaat rijden.

Dit werkte in eerste instantie niet omdat ik de label in mijn header had gezet waar een z-index van -1 op staat, waardoor de label unclickable werd. Hierna werkte het nog steeds niet. Ik ben online gaan zoeken en kwam erachter dat css de structuur van de html leest van boven naar beneden. Hierdoor moest de label en input boven de auto staan. Echter werkte dit nog steeds niet. Ik heb dit op een laag pitje gezet en ben vervolgens verder gegaan met wat andere dingen.

De h2 van de grid items (de koppen van de groepen) schaalde niet mee. Hiervoor heb ik clamp gebruikt, iets dat ik in de kickoff week bestudeerd heb en nog niet zeker wist hoe ik het precies moest gebruiken.

Hierna was het tijd voor een themales met animatie. Hier heb ik veel dingen geleerd die ik weer kan gebruiken in dit project.

Ik ben vervolgens weer verder gaan kijken naar de interactie met mijn auto. Hier heb ik mijn code vergeleken met een voorbeeld online maar ik werd hier niet wijzer van. Uiteindelijk heb ik Vasilis om hulp gevraagd. De fout zat het dus in dat mijn input niet voor de main stond maar erin. Hierdoor kon de css dus geen main na de input vinden.

Nu dat eindelijk werkt en ik mijn autootje heb zien rijden krijg ik gelijk inspiratie voor andere dingen. Het lijkt mij leuk om met animatie de auto af te laten slaan en misschien ook een knipperlicht te maken. Hier ben ik vervolgens mee aan de slag gegaan.

Na een klein beetje stuntelen en vragen hoe ik een child element kan betrekken in een animatie is dit mij gelukt. Ik dacht eerst dat ik de child element aan kon roepen binnen de animatie. Dit was niet gemakkelijk dacht ik en zo ben ik op onderzoek gegaan of dit kon. Ik kon dit nergens vinden en heb toen om raad gevraagd bij Vasilis. Die zei dat ik ook een animatie op de koplamp kan doen en deze een delay geven. Hiermee behaal ik wel wat ik wil. 

### Week 3

<strong>Dag 5</strong></br>
Vandaag ben ik begonnen met het responsive maken van de rit van de auto. Dit had ik in de tussentijd getest nadat ik een bug verholpen had waarbij de auto gelijk naar links reed. Dit heb ik opgelost door middel van een vaste hoogte te zetten op het "gebouw" waar de auto langs rijdt.

Hierna heb ik kleine aanpassingen gedaan aan de tekst zelf zoals de subtitels van de "gebouwen" in hetzelfde font gezet als de titels en quotes erg mooi vormgegeven op basis van een voorbeeld die ik online gevonden had en aangepast heb naar mijn stijl.

<img src="https://github.com/ROEL2407/City_menu/blob/main/wiki_images/quote.png">

Daarna ben ik online gaan zoeken hoe ik mijn idee van een stad meer kan verzorgen. Hierdoor ben ik gaan zoeken hoe je een boom kan maken met CSS. Dit was niet echt te vinden. Ik heb toen een voorbeeld gevonden van een stoplicht. Deze heb ik vervolgens in de grootte gemaakt die ik nodig had en een paal erbij gevoegd. Omdat ik wat meer de diepte in het design van het verkeerslicht wilde krijgen ben ik met transform: skew; aan de gang gegaan. Dit was iets wat ik ooit gebruikt had, door MDN was dit vrij makkelijk te begrijpen en staat het stoplicht iets gedraaid.

S'avonds heb ik nog gechecked of het aanpassen van de height voor de autorit gewerkt heeft. ik ben op een ander scherm gaan kijken en hier werkte het ook goed.

<strong>Dag 6</strong></br>
Vandaag ben ik begonnen met het dupliceren van mijn stoplicht. Door de functie -moz-element te gebruiken kan ik een element met de child elementen dupliceren. Dit werkt wel alleen nog in Firefox aangezien het nergens anders nog gesupport wordt.

Nadat ik mijn stoplicht gedupliceerd had, kwam ik erachter dat transform skew roet in het eten gooide. De normale grootte van het element wordt gepakt en er wordt niet gekeken naar skew, hierdoor vallen er delen van mijn stoplicht weg. De hoogte of de breedte van het nieuwe stoplicht aanpassen had geen nut. Hierdoor heb ik de skew van het initiële stoplicht veranderd naar de gedupliceerde versie.

Chrome:<br />
<img src="https://github.com/ROEL2407/City_menu/blob/main/wiki_images/stoplicht_chrome.PNG"><br />
Firefox:<br />
<img src="https://github.com/ROEL2407/City_menu/blob/main/wiki_images/stoplicht.PNG">


Hierna ben ik begonnen met ingrediënten uitzoeken die een allergische reactie kunnen veroorzaken. Hier wil ik een strong omheen zetten met een andere kleur dan de normale tekst zodat duidelijk te zien is, dat de ingrediënten erin zitten.

Doordat ik niet veel tijd meer heb en ook nog de print style moet doen heb ik gekozen voor font awesome iconen. Echter zijn sommige betaald en wil ik daar niet vor betalen. Hierdoor heb ik de vorm overgenomen in Illustrator en het svg path gebruikt voor een clip path. Het svg path werkte alleen niet gelijk, ik heb Vasilis hiervoor om raad gevraagd en die raadde mij aan om [SVGOMG](https://jakearchibald.github.io/svgomg/) te gebruiken. Dit optimaliseerd de svg en dus ook het path. Met dit path lukte het echter nog steeds niet. Ik heb het vervolgens in een [online converter](https://path-to-points.netlify.app/) gezet die een svg path omgooit naar een cip path. Hierdoor kreeg ik geen error meer, maar het icoon was nog steeds niet te zien. Dit kwam uiteindelijk doordat ik geen background-color aangegeven had wat erg logisch is.

Het volgende probleem was dat het icoon te groot was voor de converter. Ik heb vervolgens in Illustrator het icoon kleiner gemaakt en dit werkte.

Na de iconen gemaakt te hebben, heb ik eerst prioriteit gelegd bij het print style die ik er heel graag in wil hebben. Als eerste heb ik het heel erg simpel gemaakt door overbodige styling te reverten binnen het print stylesheet. Ik kwam na wat zwoegen achter dat display grid en page breaks niet samen werken. Hierna heb ik display flex in plaats van display grid geprobeerd maar ik kreeg hetzelfde resultaat. Uiteindelijk heb ik, om hetzelfde resultaat te krijgen, float left op de sections gezet en een width van 40% zodat ze in paren naast elkaar komen te staan.

<img src="https://github.com/ROEL2407/City_menu/blob/main/wiki_images/print.PNG">

### Week 4

<strong>Dag 7</strong></br>
Vandaag ben ik begonnen met het respnsive maken van de gehele applicatie. Dit was vrij snel gedaanwaardoor ik snel door kon. Ik had nog een paar punten die ik wilde doen op deze laatste dag. Deze heb ik dan ook bij mijn [Issues](https://github.com/ROEL2407/City_menu/issues) neergezet. Vervolgens heb ik mijn animatie button vormgegeven. Na eindeloos bedenken wat ik wilde, heb ik mede door functionaliteitredenen van de animatie van de button het zo gemaakt dat het lijkt op een soort trapenhuisje richting het dak. Hierna ben ik mijn readme verder gaan schrijven en ben ik gaan kijken of ik nog kleine dingen ernaast kon doen zoals licht vanuit de koplampen met een darkmode.
