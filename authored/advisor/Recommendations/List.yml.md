# `management.azure.com.advisor.recommendations.list`

## `summary`
Ruft die zwischengespeicherten Empfehlungen für ein Abonnement ab. Die Empfehlungen sind generiert oder durch Aufrufen von GenerateRecommendations berechnet.

## `uriParameters[name="subscriptionId"]/description`
Die Azure-Abonnement-ID.

## `uriParameters[name="api-version"]/description`
Die Version der API mit der Clientanforderung verwendet werden soll.

## `uriParameters[name="$filter"]/description`
Der Filter, um die Empfehlungen anzuwenden.

## `uriParameters[name="$top"]/description`
Die Anzahl der Empfehlungen pro Seite, wenn eine ausgelagerte Version dieser API verwendet wird.

## `uriParameters[name="$skipToken"]/description`
Die Seite-Fortsetzungstoken für die Verwendung mit einem ausgelagerten Version dieser API.

## `responses[name="200 OK"]/description`
OK. Erfolgreich abgerufen zwischengespeicherte Empfehlungen.

## `definitions[name="ResourceRecommendationBaseListResult"]/description`
Die Liste der Empfehlungen von Advisor.

## `definitions[name="ResourceRecommendationBaseListResult"]/properties[name="nextLink"]/description`
  
Der Link zum Abrufen der nächsten Seite von Empfehlungen verwendet.

## `definitions[name="ResourceRecommendationBaseListResult"]/properties[name="value"]/description`
  
Advisor-Empfehlung.

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


