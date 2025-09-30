# Over deze architectuur

## Context

De context van deze architectuur is al op diverse plaatsen beschreven en wordt gezien als bekend en uitgangspunt.

- Zie [Common Ground website](https://commonground.nl/).
- Zie [Realisatiekoers Common Ground](https://commonground.nl/page/view/f9c0b4bc-fbe5-4c2e-8fa5-d747a52fd58e/realisatiekoers-common-ground).
- Zie [GEMMA Online, Thema-architectuur Common Ground](https://www.gemmaonline.nl/wiki/Thema-architectuur_Common_Ground).

## Focus op 'Generieke Dienstverlening'

De huidige focus van Common Ground zijn de generieke aspecten van dienstverlening. (Zie [realisatiekoers](https://commonground.nl/page/view/f9c0b4bc-fbe5-4c2e-8fa5-d747a52fd58e/realisatiekoers-common-ground) en [programmaplan](https://commonground.nl/page/view/99b21b0c-06d7-46b6-b870-b76d9689e34e/programma-common-ground)).

Vaak noemen we dit kortweg 'Generieke Dienstverlening', maar dat is goed beschouwd een beetje vreemde term. Burger en ondernemers hebben immers behoefte aan 'specifieke' dienstverlening. Vandaar dat we in de architectuur praten over `Generieke Dienstverleningselementen` (`GDE's`). Dat zijn elementen die we - ongeachte het vakgebied of domein - nodig hebben in onze dienstverlening.

## Introductie (in beelden)

<a href="./introductie/Introductie_DIDO.pdf">
  <img src="./introductie/Introductie_DIDO.png" width="70%">
</a>

_Klik op de afbeelding om de PDF in te zien._

## Introductie (in tekst)

### Op welk 'Doel' richt deze architectuur zich?

Het 'doel' waarop deze architectuur zich richt is niet enig eindbeeld dat bestaat bij de visie Common Ground. Bijvoorbeeld een landschap waarin alle informatiekundige principes volledig zijn doorgevoerd. We richten ons nadrukkelijk op een landschap waarin dat nog niet volledig is gebeurd.

Zo gaan we er van uit dat:

- Er vakapplicaties bestaan. Niet alle processen zijn gedefinieerd in talen zoals BPMN, CMMN of DMN en 'leven' in generieke procesengines. (We bemoeien ons overigens ook niet met de vraag of dit kan en wenselijk is).
- We in vakapplicaties processen en gegevens nog niet volledig hebben kunnen scheiden.

## De bouwstenen van deze architectuur: Generieke Dienstverleningselementen (GDE's)

We spraken eerder over 'Generieke aspecten van de dienstverlening'. Een paar voorbeelden: Toegangsverlening, het informeren van klanten vanuit een proces, duurzame toegankelijkheid of logging i.v.m. privacy en security.

In deze architectuur vertalen we dit soort aspecten naar concretere bouwblokken: `Generieke Dienstverleningselementen`. Je zou dit kunnen zien als 'mentale' bouwblokken. Ieder van deze bouwblokken wordt nader uitgewerkt. Uiteindelijk leidt dat tot componenten die ontworpen en gemaakt kunnen worden zoals software services en registers.

We onderscheiden drie categorieën van `Generieke Dienstverleningselementen`:

1. [`Doelgerichte functies`](./doelgerichte-functies/index.md): Functies die vanuit een specifiek perspectief of behoefte kijken naar de kernconcepten in de gemeente.
2. [`Kernfuncties`](./kernfuncties/index.md): Functies die vrijwel iedere applicatie nodig heeft om te kunnen functioneren.
3. [`Kernconcepten`](./kernconcepten/index.md): De fundamentele concepten die de basis vormen voor dienstverlening.

De GDE's komen samen in [dit overzicht](./index.md).

## Wat hopen we met deze architectuur te bereiken?

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
