# Out of Stock - klikbare prototypes

Klikbare prototypes voor Out of Stock 2.0: verenigingen die materiaal delen, lenen, doorgeven
en hergebruiken in plaats van kopen of huren. Gemaakt door Statik als gespreksinstrument.

Scenario doorheen alle schermen: Lien, materiaalmeester bij Chiro Heverlee in Deelnetwerk Leuven,
organiseert een eetfestijn voor 80 mensen.

## De vier prototypes

| Voor wie | Wat | Link |
|---|---|---|
| Verenigingen, op de telefoon | De app in het veld (feed, zoeken, lenen, aanbieden) | [index.html](index.html) |
| Verenigingen, op de laptop | Desktop-versie van diezelfde app | [app.html](app.html) |
| Materiaalmeester | Inventarisbeheer van de eigen vereniging | [inventaris.html](inventaris.html) |
| Coach en gemeente | Netwerk-dashboard en continuïteit | [beheer.html](beheer.html) |

Daarnaast zijn er drie MVP-stukken:

- **De basis-MVP (klikbaar)**: [basis-mvp.html](basis-mvp.html). De heel basic versie volgens de
  featurelijst van Anton: publieke catalogus van alle materialen zonder login (uitgebreide filters,
  deelbare link en aanvraagformulier per object, contactgegevens achter een klik en per vereniging
  instelbaar), een achterkant per vereniging (leenstatus beschikbaar/uitgeleend/even niet,
  aanvragen met mailmelding, materiaal toevoegen, sessie boeken met de deelcoach) en een
  deelcoach-overzicht (aangesloten verenigingen, activiteit, deelscan-status, accountbeheer).

- **De minimale versie (klikbaar)**: [mvp.html](mvp.html). Alleen de Excel wordt vervangen door
  een levende "Wie heeft wat"-catalogus (gevuld met de echte data uit piloot Leuven 1.0), met
  simpel beheer per vereniging en een handmatige telling voor de deelcoach. De transactie blijft
  volledig in WhatsApp.
- **De MVP met aanvraagflow (journey)**: [mvp-journey.html](mvp-journey.html). Eén doorlopend
  voorbeeld in zeven stations (van de link in de WhatsApp-groep tot het rapport voor de gemeente)
  plus een volledige inventaris van wat de tool omvat, per gebruiker, met nice-to-have-labels.
  Kern: de aanvraag gebeurt in de tool en telt zichzelf, het gesprek blijft in WhatsApp.

De vier prototypes bovenaan zijn de droomversie en dienen als roadmap.

Bovenaan (of via de dev-knoppen op de mobiele versie) spring je tussen de schermen.
De knop **Ontwerpnotities** toont per scherm waarom het zo ontworpen is.

## Feedback geven (comment-tool)

Op elke pagina zit een feedbacklaag:

- Druk **C** (of klik de blauwe **+** rechtsonder) en klik dan ergens om een genummerde pin te plaatsen.
- Laat een opmerking achter met categorie (UX, Business Rule, Copy, Technisch) en prioriteit (Must/Should/Nice).
- Druk **H** om pins te tonen of verbergen.
- Het lijst-icoon opent het paneel met alle opmerkingen, filterbaar.
- Het download-icoon exporteert alles als een markdown-lijst.

Let op: de comments worden in je eigen browser bewaard (localStorage). Wil je ze met iemand delen,
exporteer dan de markdown-lijst en stuur die door. Voor centraal verzamelde feedback is later een
kleine backend nodig.

## Status

Prototype, geen werkend product. Geen echte database, login of betaling. Bedoeld om abstracte
discussies over platformkeuze, businessmodel en beheer te vervangen door reactie op echte schermen.
