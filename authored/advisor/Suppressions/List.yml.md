# `management.azure.com.advisor.suppressions.list`

## `summary`
Ruft die Liste der erneute Erinnerung festgelegt oder "verworfen" Unterdrückungen für ein Abonnement ab. Die erneute Erinnerung festgelegt oder "verworfen"-Attribut eine Empfehlung wird als eine Unterdrückung bezeichnet.

## `uriParameters[name="subscriptionId"]/description`
Die Azure-Abonnement-ID.

## `uriParameters[name="api-version"]/description`
Die Version der API mit der Clientanforderung verwendet werden soll.

## `responses[name="200 OK"]/description`
OK. Haben erfolgreich alle Unterdrückungen in einem Abonnement.

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


