# `management.azure.com.advisor.suppressions.create`

## `summary`
Ermöglicht die erneute Erinnerung festgelegt oder "verworfen"-Attribut eine Empfehlung. Das erneute Erinnerung festgelegt oder "verworfen"-Attribut wird als eine Unterdrückung bezeichnet. Verwenden Sie diese API, erstellen oder aktualisieren die erneute Erinnerung festgelegt oder "verworfen" Status der Empfehlung.

## `uriParameters[name="resourceUri"]/description`
Der vollqualifizierte Azure Resource Manager-Bezeichner der Ressource, auf die sich die Empfehlung bezieht.

## `uriParameters[name="recommendationId"]/description`
Die Empfehlung-ID.

## `uriParameters[name="name"]/description`
Der Name der Unterdrückung.

## `uriParameters[name="api-version"]/description`
Die Version der API mit der Clientanforderung verwendet werden soll.

## `responses[name="200 OK"]/description`
OK. Unterdrückung erstellt.

## `definitions[name="SuppressionContract"]/description`
Die Details der Regel erneute Erinnerung festgelegt oder "verworfen"; z. B. Dauer, Namen und die Regel zugeordnete GUID.

## `definitions[name="SuppressionContract"]/properties[name="properties.suppressionId"]/description`
  
Die GUID, die Unterdrückung werden soll.

## `definitions[name="SuppressionContract"]/properties[name="properties.ttl"]/description`
  
Die Dauer, für die die Unterdrückung gültig ist.

## `definitions[name="SuppressionContract"]/properties[name="id"]/description`
  
Die Ressourcen-ID.

## `definitions[name="SuppressionContract"]/properties[name="name"]/description`
  
Der Name der Ressource.

## `definitions[name="SuppressionContract"]/properties[name="type"]/description`
  
Der Typ der Ressource.


