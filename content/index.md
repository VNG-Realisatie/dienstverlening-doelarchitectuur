---
title: Overzicht generieke dienstverleningselementen
draft: true
description: Overzicht (op hoofdlijnen) van generieke dienstverleningselementen
category: none
---

# Overzicht (op hoofdlijnen) van generieke dienstverleningselementen

Direct naar: [`Doelgerichte functies`](./doelgerichte-functies/index.md), [`Kernconcepten`](./kernconcepten/index.md), [`Kernfuncties`](./kernfuncties/index.md).

<img src="./img/overzicht_op_hoofdlijnen_van_generieke_dienstverleningselementen.svg" alt="Overzicht in Archimate van generieke dienstverleningselementen en relaties daartussen" title="Overzicht op hoofdlijnen van generieke dienstverleningselementen en relaties daartussen" style="width: 100%;">

Zoals in [de introductie](/over_deze_architectuur.md#introductie-in-beelden) toegelicht onderkennen we drie soorten `Generieke Dienstverleningselementen`.

In het midden zien we een aantal [`Kernconcepten`](./kernconcepten/index.md) (oranje). Die vormen een abstractie van wat zich aan de binnenkant van gemeentelijke uitvoering afspeelt. Deze abstractie beperkt zich tot de informatie die nodig is om een set [`Doelgerichte functies`](./doelgerichte-functies/index.md) (groen) te kunnen leveren. Die vereisen vaak inzage in bij primaire taakuitvoering ontstane informatie. In sommige gevallen zijn daarnaast beperkte bewerkingen van die informatie. Bijvoorbeeld als een inwoner de MijnOmgeving gebruikt om bij een aanvraag extra informatie aan te leveren.

Aan de linker en rechterkant zien we een aantal [`Kernfuncties`](./kernfuncties/index.md): generieke functionaliteit die in de meeste applicaties voorkomt. Rechts onder is voor de volledigheid het datagedreven werken getoond. Een onderwerp waarvan de uitwerking buiten de scope van deze doelarchitectuur valt (Zie [Gemeentelijk GegevensModel](https://www.gemeentelijkgegevensmodel.nl/)).

<img src="./img/legenda.svg" alt="Legenda die de gebruikte elementen en hun relaties verklaart" title="Legenda" style="float: left; width: 38%">

// TODO: Indeling veranderen comform introductie? -> Doelgerichte functies boven, kernconcepten in het midden, datagedrevenwerken onder? En dan functies links en rechts?

// TODO: Menu hieronder weg? Moet nu zowel op pagina's als hier onderhouden worden.

## Detailviews voor doelgerichte functies

- [Actieve openbaarmaking](./doelgerichte-functies/actieve-openbaarmaking.md)
- [Duurzaam toegankelijk bewaren en beheren](./doelgerichte-functies/duurzaam-toegankelijk-bewaren-en-beheren.md)
- [Interactieve (omnichannel) dienstverlening](./doelgerichte-functies/interactieve-omnichannel-dienstverlening.md)
- [Publicatie van product- en dienstinformatie](./doelgerichte-functies/publicatie-van-product-en-dienstinformatie.md)
- [Verantwoording gebruik persoonsgegevens](./doelgerichte-functies/verantwoording-gebruik-persoonsgegevens.md)

## Detailviews voor kernfuncties

- [Authenticatie](./kernfuncties/authenticatie.md)
- [Compliance management](./kernfuncties/compliance-management.md)
- [Toegangsverlening](./kernfuncties/toegangsverlening.md)
- [Vernietigen en verwijderen](./kernfuncties/vernietigen-en-verwijderen.md)

## Detailviews voor kernconcepten

### Specificatie

- [Bedrijfsprocesdefinitie](./kernconcepten/specificatie/bedrijfsprocesdefinitie.md)
- [Product- of dienstdefinitie](./kernconcepten/specificatie/product-of-dienstdefinitie.md)
- [Verzoektype](./kernconcepten/specificatie/verzoektype.md)

### Personeelsmanagement en relatiebeheer

- [Interne actor](./kernconcepten/personeelsmanagement/interne-actor.md)
- [Partij](./kernconcepten/relatiebeheer/partij.md)

### Uitvoering

- [Contact](./kernconcepten/uitvoering/contact.md)
- [Gevolg](./kernconcepten/uitvoering/gevolg.md)
- [Handeling](./kernconcepten/uitvoering/handeling.md)
- [Taak](./kernconcepten/uitvoering/taak.md)
- [Verzoek](./kernconcepten/uitvoering/verzoek.md)

### Documentatie

- [Communicatie-artefact](./kernconcepten/documentatie/communicatie-artefact.md)
- [Werkdossier](./kernconcepten/documentatie/werkdossier.md)
