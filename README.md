| Eigenaar | Ingevuld door |
| --- | --- |
| Kenniscentrum architectuur | Ivo Hendriks |

# Dienstverlening Doelarchitectuur (DIDO)

(Eerder gebruikte afkorting: DIA - Dienstverlening (doel)Architectuur. Maar daarin ontbreekt dat het nadrukkelijk om een 'doel' architectuur gaat.)

## Inhoudsopgave

- [Status](#status)
- [Over deze architectuur](#over-deze-architectuur)
- [De bouwstenen van deze architectuur: Generieke Dienstverleningselementen (GDE's)](#de-bouwstenen-van-deze-architectuur-generieke-dienstverleningselementen-gdes)
- [Het DIDO-team](#het-dido-team)
- [Relatie met andere architecturen en initiatieven](#relatie-met-andere-architecturen-en-initiatieven)

Direct naar:

- [`Overzicht (op hoofdlijnen) van dienstverleningselementen`](./content/index.md)
- [`Doelgerichte functies`](./content/doelgerichte-functies/index.md)
- [`Kernfuncties`](./content/kernfuncties/index.md)
- [`Kernconcepten`](./content/kernconcepten/index.md)

## Status

Zie 'Wat hopen we met deze architectuur te bereiken?' hieronder voor onze plannen op hoofdlijnen. We beschrijven daarin drie doelen: `overzicht`, `inzicht` en `mogelijke transitie`.

Op dit moment geven we een eerste `overzicht` in de benodigde elementen en geven we voor een deel van de elementen `inzicht`. Vanuit het architectuurteam van Common Ground wordt gewerkt aan een overzicht van alle bestaande componenten dat we nodig hebben voor de `mogelijke transitie`.

Dit is een eerste concept, bedoeld om met elkaar in gesprek te gaan. Het architectenteam van Common Ground gaat dit gesprek organiseren.

## Over deze architectuur

### Context

De context van deze architectuur is al op diverse plaatsen beschreven en wordt gezien als bekend en uitgangspunt.

- Zie [Common Ground website](https://commonground.nl/).
- Zie [Realisatiekoers Common Ground](https://commonground.nl/page/view/f9c0b4bc-fbe5-4c2e-8fa5-d747a52fd58e/realisatiekoers-common-ground).
- Zie [GEMMA Online, Thema-architectuur Common Ground](https://www.gemmaonline.nl/wiki/Thema-architectuur_Common_Ground).

### Focus op 'Generieke Dienstverlening'

De huidige focus van Common Ground zijn de generieke aspecten van dienstverlening. (Zie [realisatiekoers](https://commonground.nl/page/view/f9c0b4bc-fbe5-4c2e-8fa5-d747a52fd58e/realisatiekoers-common-ground) en [programmaplan](https://commonground.nl/page/view/99b21b0c-06d7-46b6-b870-b76d9689e34e/programma-common-ground)).

Vaak noemen we dit kortweg 'Generieke Dienstverlening', maar dat is goed beschouwd een beetje vreemd term. Burger en ondernemers hebben immers behoefte aan 'specifieke' dienstverlening. Vandaar dat we in de architectuur praten over `Generieke Dienstverleningselementen` (`GDE's`). Dat zijn elementen die we - ongeachte het vakgebied of domein - nodig hebben in onze dienstverlening.

### Op welk 'Doel' richt deze architectuur zich?

Het 'doel' waarop deze architectuur zich richt is niet enig eindbeeld dat bestaat bij de visie Common Ground. Bijvoorbeeld een landschap waarin alle informatiekundige principes volledig zijn doorgevoerd. We richten ons nadrukkelijk op een landschap waarin dat nog niet volledig is gebeurd.

Zo gaan we er van uit dat:

- Er vakapplicaties bestaan. Niet alle processen zijn gedefinieerd in talen zoals BPMN, CMMN of DMN en 'leven' in generieke procesengines. (We bemoeien ons overigens ook niet met de vraag of dit kan en wenselijk is).
- We in vakapplicaties processen en gegevens nog niet volledig hebben kunnen scheiden.

### Wat hopen we met deze architectuur te bereiken?

We hopen met deze architectuur:

1. Een `overzicht` te geven van de `Generieke Dienstverleningselementen` die we nodig hebben.

   We hebben dit overzicht nodig om de ontwikkeling te kunnen overzien en te sturen op hoofdlijnen.

2. `Inzicht` te geven in deze `Generieke Dienstverleningselementen`.

   Inzicht:
   - Wat bedoelen we precies?
   - Zijn er wellicht verschillende interpretaties, en zo ja, kunnen die naast elkaar bestaan of is dat onwenselijk?

   Dat inzicht helpt bij het beantwoorden van allerlei vragen.
   Een selectie van vragen ter illustratie:

   - Is dit iets op Europees, landelijk of gemeentelijk niveau?
   - Is het er al?
     - Ja:
       - Zijn er meerdere varianten of alternatieven? Wat zijn de verschillen? Hoe wezenlijk zijn die?
       - Kunnen we wat er is al inzetten of moet er nog iets gebeuren?
       - Hoe verschilt wat er is van wat we uiteindelijk voor ogen hebben?
       - Wat moeten we doen om bij het doel te komen?
     - Wordt aan gewerkt:
       - Gaat dat de goede kant op?
       - Op welke termijn kunnen we het inzetten?
       - Kunnen we daar wel op wachten?
     - Nee:
       - Is er een ontwerp? Hoe komen we daaraan?
       - ...

   Door dit soort vragen te beantwoorden komen we tot werkpakketten en kunnen we deze prioriteren en beleggen.
   (N.B. Deze activiteit behoort nadrukkelijk _NIET_ tot de doelarchitectuur).

3. Een `mogelijke transitie` te beschrijven.

   Door te beschrijven wat we nu al hebben en dit vergelijken met het doel.

## De bouwstenen van deze architectuur: Generieke Dienstverleningselementen (GDE's)

We spraken eerder over 'Generieke aspecten van de dienstverlening'. Een paar voorbeelden: Toegangsverlening, het informeren van klanten vanuit een proces, duurzame toegankelijkheid of logging i.v.m. privacy en security.

In deze architectuur vertalen we dit soort aspecten naar concretere bouwblokken: `Generieke Dienstverleningselementen`. Je zou dit kunnen zien als 'mentale' bouwblokken. Ieder van deze bouwblokken wordt nader uitgewerkt. Uiteindelijk leidt dat tot componenten die ontworpen en gemaakt kunnen worden zoals software services en registers.

We onderscheiden drie categorieën van `Generieke Dienstverleningselementen`:

1. `Doelgerichte functies`: Functies die vanuit een specifiek perspectief of behoefte kijken naar de kernconcepten in de gemeente.
2. `Kernfuncties`: Functies die vrijwel iedere applicatie nodig heeft om te kunnen functioneren.
3. `Kernconcepten`: De fundamentele concepten die de basis vormen voor dienstverlening.

## Het DIDO-team

Het DIDO-team is bewust een heel klein team. Met mensen die kennis inbrengen uit verschillende perspectieven en een brug kunnen vormen naar verschillende initiatieven en organisatie onderdelen:

- Kennis over Common Ground
- Kennis over MijnServices dienstverlening (Omnichannel)
- Kennis over allerlei ontwikkelingen overheidsbreed (GDI, FDS, nieuwe wetgeving)
- Kennis over registers, interactiepatronen en API's

Helaas is het geen team dat vijf dagen per week aan deze architectuur kan werken. Als dat wel kon, dan hadden we deze kennis niet kunnen inbrengen en de noodzakelijke verbinding niet kunnen leggen. Het is laveren: Wil je maximaal tempo, dan heb je een full-time team nodig. Wil je geen ivoren toren, dan heb je mensen nodig die bezig zijn met concrete ontwikkelingen.

Gegeven deze constructie beperken we ons tot:

- het geven van `overzicht`
- het geven van `inzicht`
- het beschrijven van een `mogelijke transitie`

Daarnaast:

- Onderhouden we de architectuur door voortschrijdend inzicht te verwerken.
- Zijn we beschikbaar om bij knelpunten in de verdere uitwerking mee te denken. (Indien die deze knelpunten de architectuur raken).

Wat ook moet gebeuren, maar helaas niet in één dag per week lukt:

- Het afstemmen van deze architectuur met belanghebbenden.

  We denken in de richting van een 'Architectuurgroep' waarin we samen de conceptontwerpen en vraagstukken doornemen.

- Maken van een backlog met werkpakketten, prioritering hier van etc.

  Uiteraard is DIDO een bron voor veel werkpakketten, maar er zijn zeker ook andere invalshoeken. Hoe we tot een backlog komen en hoe we dit bewaken moet nog bepaald worden.

- Uitwerken van gedetailleerde ontwerpen.

  De doelarchitectuur wil `overzicht` en `inzicht` geven. Daarmee hebben we nog geen gedetailleerde ontwerpen. Denk bijvoorbeeld aan een concrete API voor de vastlegging van interacties met klanten. Dit is nu juist het werk dat vanuit een backlog toegewezen wordt of gevraagd wordt van allerlei teams die samen werken om Common Ground te realiseren.

Er wordt nog nagedacht hoe en waar we dit in de organisatie(s) kunnen beleggen.

## Relatie met andere architecturen en initiatieven

### GEMMA (Gemeentelijke Model Architectuur)

Deze doelarchitectuur is een concretisering van GEMMA. Waar GEMMA de algemene kaders en principes beschrijft voor gemeentelijke informatievoorziening, werkt deze doelarchitectuur die uit voor de `Generieke Dienstverleningselementen`.

### MijnServices dienstverlening (Omnichannel)

Het MijnServices team werkt allerlei onderdelen uit die benoemd worden in deze architectuur.

### Lopende initiatieven (G4, Dimpact, ZGW, etc.)

Deze initiatieven vormen het vertrekpunt voor de transitie naar de doelarchitectuur. Via werkpakketten moet gekeken worden hoe we van deze bestaande componenten stap voor stap bij de gewenste eindtoestand komen.

De doelarchitectuur vervangt deze initiatieven niet, maar biedt een kader om:

- Te beoordelen hoe bestaande oplossingen aansluiten bij de gewenste richting
- Lacunes te identificeren waar nog oplossingen ontwikkeld moeten worden  
- Samenhang te bewaken tussen verschillende initiatieven en componenten
- Fundamentele knelpunten in die samenhang te benoemen en oplossingen aan te dragen

### Gemeentelijk Gegevensmodel (GGM)

Het GGM richt zich op datagedreven werken. Bij datagedreven werken worden gegevens gebruikt uit allerlei domeinen, inclusief de gegevens die voorkomen binnen de `Generieke Dienstverleningselementen`. Het GGM volgt dus de gegevensmodellen van de detailontwerpen die horen bij deze in deze architectuur benoemde onderdelen.
