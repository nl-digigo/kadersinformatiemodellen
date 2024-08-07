# Richtlijnen

Dit hoofdstuk beschrijft de richtlijnen, verdeeld naar onderwerp. Per richtlijn is aangegeven welke van de FAIRQ-eigenschappen het invult. De F en A gaan voornamelijk over toegang tot en beschikbaarheid van het informatiemodel, de I en R over technische operabiliteit en de Q voornamelijk over de kwaliteit van de beheerorganisatie.

## Richtlijnen voor het ontwikkelen van een OTL

**Waarom**

Het ontwikkelen van een OTL is meer dan een technisch project. Een succesvolle OTL dient het doel waarvoor hij ontwikkeld is, wordt gevonden, wordt veel toegepast en hergebruikt, beweegt mee met de wensen van de gebruikers, wordt ondersteund, en langjarig beheerd. Om dit te bereiken is het van belang om op organisatie- en procesniveau de juiste stappen te zetten. 

**Richtlijnen**

| FAIRQ   |          Kenmerk          | Beschrijving                                                                                                                                                                                                                                                         |
|---------|---------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Q       | Organisatie               | Breng de juiste stakeholders bij elkaar en organiseer samenwerking. Regel mandaat en budget en stel een planning op, en neem hier de beheerfase ook in mee. Zorg dat iedereen die input wil leveren dit ook kan doen, maar zorg tegelijkertijd voor een heldere procedure om tot beslissingen te komen. [BOMOS](https://www.logius.nl/domeinen/infrastructuur/bomos/documentatie) is een hulpmiddel voor het opzetten van een beheer- en ontwikkelorganisatie voor open standaarden en kan hierbij als inspiratie dienen, vooral [het hoofdstuk over het opzetten van een ontwikkel- en beheerorganisatie](https://gitdocumentatie.logius.nl/publicatie/bomos/verdieping/#de-ontwikkel-en-beheerorganisatie-activiteit-governance). |
| Q       | Doel                      | Formuleer een duidelijk en (liefst) meetbaar doel met een afgebakende scope. Het kan hierbij helpen om concrete use cases op te stellen of een beoogd gebruik. Voorbeelden zijn bijvoorbeeld het spreken van één taal binnen een project of organisatie, data-uitwisseling met een (specifieke) opdrachtnemer ondersteunen of het maken van een kostenraming automatiseren. |
| R       | Inventariseer informatiebronnen | Inventariseer welke informatiebronnen je nodig hebt om de use case af te dekken. Denk aanbijvoorbeeld wetgeving, normen, domeinstandaarden en referentietabellen.                                                                                                    |
| R       | Inventariseer bestaande standaarden | Inventariseer welke OTLen en andere standaarden als basis kunnen dienen voor de OTL en bouw hierop voort. Probeer niet het wiel zelf uit te vinden. Zie ook de richtlijnen over eenmalig registreren.                                                                          |
| F/A     | Publicatie                | Publiceer je OTL online, voorzien van een goede beschrijving en documentatie. Voor meer details hierover zie de richtlijnen voor publicatie.                                                                                                                            |
| Q       | Beheer                    | Beheer je OTL. Maak een planning voor nieuwe versies en houd de planning van onderliggende standaarden/OTL'en in de gaten. Beschrijf de verschillende rollen in het beheerproces. Organiseer ondersteuning voor gebruikers. Voor meer details hierover zie de richtlijnen voor beheer.                                         |

## Richtlijnen voor het opzetten van een woordenboek

**Waarom**

Een woordenboek is een lijst van termen en definities, waar mogelijk hiërarchisch opgezet en aangevuld met relaties tussen begrippen. Een woordenboek is bedoeld voor gebruikers om tot overeenstemming te komen over de betekenis van termen en begrippen. Om effectief te kunnen worden gebruikt moet een woordenboek bovendien goed doorzoekbaar zijn. Het is daarom belangrijk dat (i) een woordenboek altijd op dezelfde manier is opgezet en (ii) een woordenboek zo volledig mogelijk is ingevuld, inclusief bijvoorbeeld synoniemen en (niet zichtbare) zoektermen waar op gezocht kan worden.

Het doel van een woordenboek is om dezelfde taal te spreken, binnen en buiten de eigen organisatie. Een woordenboek zou daarom in principe altijd open moeten worden gepubliceerd. 

**Richtlijnen**

| FAIRQ | Kenmerk                    | Beschrijving                                                                                          |
|-------|----------------------------|-------------------------------------------------------------------------------------------------------|
| I     | SBB                        | Het woordenboek is opgezet volgens de <a href="https://profielstelselcatalogus.pldn.nl/">Standaard voor het beschrijven van begrippen (SBB)</a> van Geonovum. |
| I     | Volledigheid               | Het woordenboek wordt zo volledig mogelijk ingevuld waarbij bijvoorbeeld gebruikt wordt gemaakt van synoniemen, zoektermen, en wijzigingsnotities. |
| I     | Taxonomie                  | Het woordenboek is hiërarchisch opgezet, als taxonomie.                                               |
| I     | Bronverwijzing             | Waar mogelijk wordt verwezen naar openbare bronnen waar een begrip op is gebaseerd, zoals standaarden, wetgeving, etc. |
| I     | Thesaurus                  | Begrippen zijn aan elkaar gerelateerd, zoals in een thesaurus.                                        |

## Richtlijnen voor het opzetten van een ontologie

Op dit moment ontbreken nog richtlijnen om een ontologie op te zetten. De NEN-normcommissie <a href="https://www.nen.nl/modellering-integratie-en-interoperabiliteit-van-informatie-in-de-gebouwde-omgeving-en-procesindustrie">Modellering, integratie en interoperabiliteit van informatie in de gebouwde omgeving en procesindustrie</a> werkt aan een praktijkrichtlijn voor de NEN 2660. De verwachting is dat deze in 2024 wordt gepubliceerd.

## Richtlijnen voor eenmalig registeren, meervoudig gebruik.

**Waarom**

Dubbele registraties, overtypen van gegevens en dubbele softwareontwikkelingen zijn een bekend probleem. Daarom is het van belang om gezamenlijk te werken met dezelfde gegevens en definities. Daarmee wordt het mogelijk om eenmalig te registreren en meervoudig te gebruiken. 

Het opstellen van een goede OTL heeft als randvoorwaarde dat de opgenomen concepten/objecttypes, definities en kenmerken herkenbaar zijn, binnen en buiten de eigen organisatie. Om dit te bewerkstelligen is het belangrijk om zoveel mogelijk gebruik te maken van marktconforme standaarden. Het wiel is vaak voor een groot deel al uitgevonden.

Het volgende is een incomplete lijst van bestaande standaarden en OTL'en:

- de <a href="https://amsterdam.otl-viewer.com/">Gemeente Amsterdam OTL</a>;
- de <a href="https://otl.waternet.nl/">Waternet OTL</a>;
- de <a href="https://otl.prorail.nl/otl/">ProRail OTL</a>;
- het <a href="https://www.crow.nl/thema-s/management-openbare-ruimte/imbor/over-imbor-1">informatiemodel beheer openbare ruimte (IMBOR)</a> van CROW;
- het <a href="https://www.riool.net/applicaties/gegevenswoordenboek-stedelijk-water">gegevenswoordenboek stedelijk water (GWSW)</a> van RioNed;
- Geonovum beheert een groot aantal informatiemodellen, waaronder:
    - de <a href="https://www.geonovum.nl/geo-standaarden/informatiemodellen-nen3610-familie/gegevenscatalogus-basisregistratie-adressen-en">basisadministratie adressen en gebouwen (BAG)</a>;
    - de <a href="https://www.geonovum.nl/geo-standaarden/bgt-imgeo">basisregistratie grootschalige topografie (BGT)</a>;
    - de <a href="https://www.geonovum.nl/geo-standaarden/bro-basisregistratie-ondergrond/basisregistratie-ondergrond-imbro">basisregistratie ondergrond (BRO)</a>;
    - het <a href="https://www.geonovum.nl/geo-standaarden/informatiemodel-kabels-en-leidingen">informatiemodel kabels en leidingen (IMKL)</a>;
    - het <a href="https://www.geonovum.nl/geo-standaarden/imx-geo-semantisch-model-basis-en-kernregistraties">semantisch model basis- en kernregistraties (IMX-Geo)</a>;
    - zie voor de complete lijst het <a href="https://www.geonovum.nl/geo-standaarden">overzicht</a> van Geonovum;
- een overzicht van meer standaarden kunt u vinden op de website van <a href="https://www.bimloket.nl/ictstandaarden/">digiGO</a>.

**Richtlijnen**

| FAIRQ | Kenmerk | Beschrijving                       |
|-------|---------|------------------------------------|
| R     | Hergebruik vóór creatie    | Nieuwe OTL'en bouwen voort op bestaande OTL'en. Bestaande OTL'en worden zoveel mogelijk hergebruikt. Het introduceren van nieuwe concepten wordt tot een minimum beperkt. |
| R     | Hergebruik door verwijzing | Hergebruik van elementen gebeurt door te verwijzen naar het bronelement via zijn URI (zie ook de richtlijnen voor uniek identificeren). Bestaande elementen of eigenschappen worden niet herhaald in de nieuwe OTL. |
| R     | Hergebruik faciliteren | Indien organisaties zelf objecttypes, begrippen en definities hebben ontwikkeld, dan is het van belang om deze eenduidig te definiëren en om deze middels een woordenboek beschikbaar te stellen volgens de richtlijnen die hier voorgesteld worden. |
| R     | Benoemen relaties          | Relaties met andere OTL'en worden (kort) benoemd in de algemene beschrijving van de OTL.               |
| R     | Documenteren relaties      | Relaties met andere OTL'en zijn uitgebreid gedocumenteerd in de technische documentatie, inclusief verwijzing naar de bron-OTL'en en de gebruikte versies.  |

## Richtlijnen voor uniek identificeren

**Waarom**

Zonder unieke identificatie kunnen de elementen van een OTL niet meervoudig worden gebruikt en kunnen ze niet door ICT-systemen worden gevonden en begrepen. Unieke identificatie is daarom een belangrijke voorwaarde voor interoperabiliteit. Daarbij is het ook van belang dat identificatie op een consistente manier is opgezet.

**Richtlijnen**

| FAIRQ | Kenmerk | Beschrijving                       |
|-------|---------|------------------------------------|
| R     | Unieke identifiers op alle niveaus    | Elementen op alle niveaus hebben een unieke identifier: (i) de dataset in zijn geheel (dus het woordenboek of de ontologie), (ii) de individuele concepten, hun eigenschappen en hun relaties, en (iii) waardenlijsten alsmede de individuele waarden. |
| R     | Consistente identifiers | Identifiers mogen niet wijzigen gedurende de levensduur van een element. |
| R     | Betekenisloze identifiers | Identifiers moeten een betekenisloze naam hebben, om te voorkomen dat een naam gewijzigd wordt gedurende de levensduur van een element. |

## Richtlijnen voor informatiemodellering

**Waarom**

De richtlijnen voor informatiemodellering hebben als doel interoperabiliteit en hergebruik te bewerkstelligen. OTL'en moeten daarom volgens dezelfde technische standaarden worden ontwikkeld. We schrijven daarom voor dat een OTL wordt ontwikkeld (of anders gepubliceerd) in RDF (linked data), volgens de <a href="https://www.nen.nl/nen-2660-2-2022-nl-291667">NEN 2660-2</a>.

<!-- De richtlijnen in deze sectie gelden voor alle soorten OTL'en. Daarnaast zijn er aanvullende richtlijnen specifiek voor woordenboeken en de relaties tussen OTL'en. Deze worden toegelicht in de volgende subsecties. Voor ontologieën zijn er nog geen praktische richtlijnen hoe deze het beste kunnen worden opgezet. Er is nog wel één richtlijn in de NEN 2660 die we hier expliciet benoemen en opnemen in de onderstaande tabel: in een ontologie moet een klasse verwijzen naar het woordenboekbegrip waar het op is gebaseerd. -->

**Richtlijnen**

| FAIRQ | Kenmerk                    | Beschrijving                                                                                          |
|-------|----------------------------|-------------------------------------------------------------------------------------------------------|
| R     | RDF     | Ontwikkel de OTL in RDF (linked data). Zie ook het <a href="https://5stardata.info/en/">vijfsterrenmodel voor open data</a>. |
| I     | NEN 2660                   | De OTL voldoet aan de <a href="https://www.nen.nl/nen-2660-2-2022-nl-291667">NEN 2660-2</a>.            |
| I     | Taal                       | De gebruikte talen voor uitwisseling zijn conform de NEN 2660-2: (relaties tussen) woordenboeken zijn opgezet in SKOS; (relaties tussen) ontologieën in RDFS, OWL en/of SHACL. |
| I     | Formaat                    | De gebruikte formaten voor uitwisseling zijn conform de NEN 2660-2: RDF-XML, Turtle of JSON-LD                            |
| R     | Documentatie               | De OTL is gedocumenteerd en de documentatie is vindbaar en toegankelijk.                              |

## Richtlijnen voor harmonisatie tussen OTL'en

**Waarom**

Bij harmonisatie wordt er een mapping gemaakt tussen twee woordenboeken of tussen twee ontologieën via harmonisatierelaties. Harmonisatie is noodzakelijk om tot gegevensuitwisseling tussen deze OTL'en te komen. Wanneer de OTL'en door verschillende organisaties worden beheerd, moet de harmonisatie als een aparte OTL met een aparte beheeropgave worden opgepakt.

**Richtlijnen**

| FAIRQ | Kenmerk                    | Beschrijving                                                                                          |
|-------|----------------------------|-------------------------------------------------------------------------------------------------------|
| I     | Matching through alignment | Relaties tussen OTL'en (voor hergebruik en harmonisatie) zijn conform <a href="https://docs.crow.nl/ontology-alignment/whitepaper/">"Ontology Matching trough alignment and extension: a Best Practice"</a> van CROW. | 
| R     | Interne harmonisatie       | Bij harmonisatie tussen OTL'en die binnen dezelfde organisatie worden beheerd, kunnen de harmonisatierelaties impliciet onderdeel zijn van een van beide OTL'en. |
| R     | Externe harmonisatie       | Harmonisatie tussen OTL'en van verschillende organisaties moet als een aparte OTL met een aparte beheeropgave worden opgepakt. |
| R     | Benoemen relaties          | Relaties met andere OTL'en worden (kort) benoemd in de algemene beschrijving van de OTL.               |
| R     | Documenteren relaties      | Relaties met andere OTL'en zijn uitgebreid gedocumenteerd in de technische documentatie, inclusief verwijzing naar de bron-OTL'en en de gebruikte versies.  |

## Richtlijnen voor publicatie

**Waarom**

Om een OTL te kunnen gebruiken, moet:
- de OTL makkelijk te vinden zijn;
- de OTL makkelijk te begrijpen zijn; er moet zijn beschreven voor wie en voor wat deze bedoeld is;
- de OTL makkelijk beschikbaar zijn; d.w.z. te bekijken en te downloaden;
- de beheerder van de OTL makkelijk te bereiken zijn voor vragen.

Dit is gevat in onderstaande richtlijnen.

**Richtlijnen**

| FAIRQ | Kenmerk                    | Beschrijving                                                                                          |
|-------|----------------------------|-------------------------------------------------------------------------------------------------------|
| F     | Naam                       | De OTL heeft een duidelijk naam die consistent wordt gebruikt over versies heen.                                                                    |
| F     | Beschrijving               | Er is een beschrijvende tekst waarin wordt toegelicht waarvoor en voor wie de OTL bedoeld is. |
| F     | Zoektermen                 | Er zijn termen gedefinieerd (synoniemen, alternatieven, zoektermen) waarop kan worden gezocht.      |
| F     | Eigenaar                   | Er is een eigenaar van de OTL. Naam en contactgegevens van het aanspreekpunt van de eigenaar zijn bekend. |
| F     | Beheerder                  | Er is een beheerder van de OTL. Naam en contactgegevens van het aanspreekpunt van de beheerder zijn bekend. |
| F     | Vindbaar                   | De OTL is, inclusief toelichting en documentatie, online vindbaar en beschikbaar.                    |
| A     | Beschikbaar                | De OTL is in zijn geheel te downloaden of kan direct worden benaderd via eene URI. Dit geldt voor de gehele OTL en de individuele elementen. |
| A     | Viewer                     | De OTL kan online worden bekeken via een viewer.                                                     |
| A     | Openheid van gebruik       | De OTL is, eventueel na betaling, voor iedereen beschikbaar om te gebruiken.                          |
| A     | Nederlandse taal           | De OTL en alle informatie eromheen zijn in het Nederlands opgesteld.                                  |
| A     | Engelse taal               | De OTL en alle informatie eromheen zijn liefst ook in het Engels opgesteld.                                      |

## Richtlijnen voor beheer

**Waarom**

Gebruikers van een OTL stemmen hun processen en systemen af op de OTL en zijn daarmee op een hele directe manier afhankelijk van hoe de OTL beheerd wordt. Goed beheer is daarom er belangrijk. Versiebeheer moet op orde zijn; er moet bewust worden omgegaan met de impact die wijzigingen kunnen hebben voor gebruikers; (grote) wijzigingen moeten worden aangekondigd; en wijzigingen tussen versies moeten goed zijn gedocumenteerd.

Dit is gevat in onderstaande richtlijnen.

**Richtlijnen**

| FAIRQ | Kenmerk                    | Beschrijving                                                                                          |
|-------|----------------------------|-------------------------------------------------------------------------------------------------------|
| Q     | Versiebeheer               | Voor woordenboeken wordt versiebeheer toegepast zoals voorgeschreven door de SBB. Voor ontologieën bestaat nog geen standaard maar zijn wel <a href="https://docs.crow.nl/wp/ldversiebeheer">verschillende strategieën</a> beschreven.                                    |
| Q     | Meest recente versie      | De meest recente versie is beschikbaar.                                                                |
| Q     | Vorige versie              | De vorige versie moet minimaal beschikbaar zijn.                                                      |
| Q     | Oudere versies             | Oudere versies zijn beschikbaar.                                                                      |
| Q     | Versieverschillen          | Verschillen tussen versies zijn toegelicht.                                                           |
| Q     | Releasekalender            | Er is een planning beschikbaar voor toekomstige versies, inclusief een indicatie van verwachte wijzigingen per wijziging. Op zijn minst wordt aangegeven of en wanneer er een nieuwe versie verwacht wordt. |
| Q     | Feedback                   | De beheerder kan benaderd worden, bijvoorbeeld om bugs te melden en features te verzoeken.            |
