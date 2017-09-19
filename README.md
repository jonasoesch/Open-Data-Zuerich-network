## Twitter Netzwerk von Open Data-Zürich

Um eine Idee zur Zusammensatzung der Open Data-Szene in der Schweiz zu erhalten, wurde der Twitter-Account von Open Data-Zürich analyisert.
[@opendatazurich](https://twitter.com/opendatazurich) ist einer der aktivsten Schweizer Accounts zum Thema.

Das Resultat ist unter [https://jonasoesch.github.io/Open-Data-Zuerich-network/](https://jonasoesch.github.io/Open-Data-Zuerich-network/) zu finden.

## Methode

Zum erstellen des Netzwerks wurde [Twecoll](https://github.com/jdevoo/twecoll) eingesetzt. Das Tool generiert ein Netzwerk aller Beziehungen 1. und 2. Grades eines Twitter-Users.

Das entstandene Netzwerk wurde mit [Gephi](https://gephi.org/) folgendermassen bearbeitet:
1. Grosse Accounts mit über 10'000 Followern wurden entfernt, weil sie oftmals einen überproportionalen Einfluss im Netzwerk haben. So lassen sich Subgruppen weniger gut ausmachen.

2. Die Knoten wurden mit dem [OpenOrd](https://github.com/gephi/gephi/wiki/OpenOrd)-Algorithmus angeordnet. *OpenOrd* eignet sich speziell gut um Cluster in einem Netzwerk sichtbar zu machen.

3. Die Darstellung des resultierenden Graphen als Webseite geschieht mit Hilfe von [Sigma.js](http://sigmajs.org/)
