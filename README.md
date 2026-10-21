# PebbleBudget

**Een rustige, lokale uitgavenplanner.** PebbleBudget helpt mensen die hun maandbudget eenvoudig willen overzien hun uitgaven handmatig bij te houden, zonder bankkoppeling. [Read this in English](en/README.md).

## Probleem en doelgroep

Een snelle aankoop is makkelijk te vergeten en niet iedereen wil een bankrekening aan een app koppelen. PebbleBudget is voor wie zelf een eenvoudig maandoverzicht wil bijhouden.

## Start

Open `index.html` in een moderne browser. Er is geen installatie, account, server of API nodig. Voor English open `en/index.html`.

## Wat werkt

- Stel een maandbudget in en bekijk uitgaven, resterend bedrag en budgetvoortgang.
- Voeg uitgaven toe met omschrijving, bedrag, datum en categorie.
- Filter per maand en verwijder een uitgave.
- Exporteer je gegevens als JSON-back-up.

## Korte demo

1. Open `index.html` en stel een maandbudget in.
2. Voeg een fictieve uitgave toe, bijvoorbeeld `Lunch` voor `12,50` euro.
3. Bekijk hoe het maandtotaal en het resterende budget worden bijgewerkt; gebruik daarna **Exporteer data** om een back-up te downloaden.

Om opnieuw te beginnen, wis de lokale sitegegevens van deze pagina in je browser. Dit verwijdert de opgeslagen gegevens permanent.

## Privacy en grenzen

Alle informatie wordt bewaard in `localStorage` van de browser en wordt niet verstuurd. De gegevens zijn niet versleuteld en kunnen verdwijnen als browserdata wordt gewist. Bewaar geen bankrekeningnummers of andere gevoelige details. PebbleBudget koppelt niet met een bank en geeft geen financieel advies.

## Techniek

Vanilla HTML, CSS en JavaScript; geen externe afhankelijkheden.

## Mogelijke vervolgstappen

- Een back-up kunnen terugzetten vanuit een JSON-bestand.
- Eigen categorieën toevoegen.
- Een afdrukbaar maandoverzicht maken.

## Ideeën voor later

Importeerbare back-up, aangepaste categorieën en een geprint maandoverzicht.

