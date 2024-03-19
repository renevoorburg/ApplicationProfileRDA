# Zeemaal

Bestand: [10_zeemaal_productie.ttl](10_zeemaal_productie.ttl)

## Entiteitenstructuur

Dit is een nadere reïficatie van [09_zeemaal.ttl](09_zeemaal.ttl) waarbij de productie tot een aparte werk-entiteit gemaakt is. Er ontstaat daarbij ook een bijbehorende expressie-entiteit. Deze expressie-entiteit omvat alle utvoeringen (expressies) van het toneelstuk. 

![Visualisatie Structuur](../../assets/10_zeemaal_rda-rdf_visualisatie.png)


## Representatie in RDA-RDF

Op werk-niveau zijn weinig kenmerken aan een productie te verbinden. Het gaat dan vooral om producer. Nodig is een manier om de category of work aan te duiden. Dit is nu gedaan met een literal, niet uit een vocabulaire. Er zal een extension-plan aangegeven kunnen worden.

De productie-gerelateerde kenmerken hebben in RDA vooral een plaats op expressieniveau. Deze zijn van de expressie als voorstelling overgeheveld naar deze nieuwe expressie als productie.

De voorstelling als expressie is in essentie een "part of" van de productie als expressie. Zie ook de visualisatie van de entiteitenstructuur.

Bestand: [10_zeemaal_productie.ttl](10_zeemaal_productie.ttl)