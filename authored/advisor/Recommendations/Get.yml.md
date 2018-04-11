# `management.azure.com.advisor.recommendations.get`

## `summary`
Ruft eine zwischengespeicherte Empfehlung Details ab.

## `uriParameters[name="resourceUri"]/description`
Der vollqualifizierte Azure Resource Manager-Bezeichner der Ressource, auf die sich die Empfehlung bezieht.

## `uriParameters[name="recommendationId"]/description`
Die Empfehlung-ID.

## `uriParameters[name="api-version"]/description`
Die Version der API mit der Clientanforderung verwendet werden soll.

## `responses[name="200 OK"]/description`
OK. Erhalten Sie ausführliche Empfehlung erfolgreich haben.

## `definitions[name="ResourceRecommendationBase"]/description`
Die Liste der Empfehlungen.

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.category"]/description`
  
Die Kategorie der Empfehlung.

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.impact"]/description`
  
Die geschäftlichen Auswirkungen der Empfehlung.

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.impactedField"]/description`
  
Der Ressourcentyp von Advisor identifiziert.

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.impactedValue"]/description`
  
Die Ressource, die von Advisor identifiziert.

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.lastUpdated"]/description`
  
Der letzte Zeitpunkt, Advisor überprüft die Gültigkeit der Empfehlung.

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.metadata"]/description`
  
Die Empfehlung-Metadaten.

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.recommendationTypeId"]/description`
  
Die Empfehlung-Type-GUID.

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.risk"]/description`
  
Das potenzielle Risiko nicht Umsetzung der Empfehlung.

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.shortDescription"]/description`
  
Eine Zusammenfassung der Empfehlung.

## `definitions[name="ResourceRecommendationBase"]/properties[name="properties.suppressionIds"]/description`


## `definitions[name="ResourceRecommendationBase"]/properties[name="id"]/description`
  
Die Ressourcen-ID.

## `definitions[name="ResourceRecommendationBase"]/properties[name="name"]/description`
  
Der Name der Ressource.

## `definitions[name="ResourceRecommendationBase"]/properties[name="type"]/description`
  
Der Typ der Ressource.

## `definitions[name="category"]/description`
Die Kategorie der Empfehlung.

## `definitions[name="impact"]/description`
Die geschäftlichen Auswirkungen der Empfehlung.

## `definitions[name="risk"]/description`
Das potenzielle Risiko nicht Umsetzung der Empfehlung.

## `definitions[name="ShortDescription"]/description`
Eine Zusammenfassung der Empfehlung.

## `definitions[name="ShortDescription"]/properties[name="problem"]/description`
  
Oder die Möglichkeit, die von der Empfehlung identifiziert.

## `definitions[name="ShortDescription"]/properties[name="solution"]/description`
  
Die Wiederherstellungsaktion an die von der Empfehlung vorgeschlagen.


