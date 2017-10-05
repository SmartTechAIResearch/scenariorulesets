Bevat scenario rule sets die bepalen welke velden / waarden requests in een scenario moeten bevatten.

Aan de hand van zo'n rule set (logische opdeling) gebeurt er lexing op tekst.

Zo zal een database query er anders uitzien en andere waarden bevatten dan een HTTP request. 

De velden worden gebruikt in een bijhorende connection proxy om een request naar een server applicatie te bouwen.

Deze rule sets worden automatisch meegenomen in de Jenkins (onze CI) vApus build job.