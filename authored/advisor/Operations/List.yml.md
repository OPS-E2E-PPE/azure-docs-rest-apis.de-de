# `management.azure.com.advisor.operations.list`

## `summary`
Listet die verfügbaren Advisor-REST-API-Vorgänge.

## `uriParameters[name="api-version"]/description`
Die Version der API mit der Clientanforderung verwendet werden soll.

## `responses[name="200 OK"]/description`
OK. Vorgangsliste wurde erfolgreich abgerufen.

## `definitions[name="OperationEntityListResult"]/description`
Die Liste der Advisor-Vorgänge.

## `definitions[name="OperationEntityListResult"]/properties[name="nextLink"]/description`
  
Der Link zum Abrufen der nächsten Seite von Vorgängen verwendet.

## `definitions[name="OperationEntityListResult"]/properties[name="value"]/description`
  
Der Vorgang von Advisor unterstützt.

## `definitions[name="OperationEntity"]/description`
Die Liste der Vorgänge.

## `definitions[name="OperationEntity"]/properties[name="name"]/description`
  
Vorgangsname: {Anbieter} / {Resource} / {Operation}.

## `definitions[name="OperationEntity"]/properties[name="display"]/description`
  
Der Vorgang von Advisor unterstützt.

## `definitions[name="OperationDisplayInfo"]/description`
Der Vorgang von Advisor unterstützt.

## `definitions[name="OperationDisplayInfo"]/properties[name="description"]/description`
  
Die Beschreibung des Vorgangs.

## `definitions[name="OperationDisplayInfo"]/properties[name="operation"]/description`
  
Die Aktion, die Benutzer ausführen können, basierend auf ihrer Berechtigungsstufe.

## `definitions[name="OperationDisplayInfo"]/properties[name="provider"]/description`
  
Dienstanbieter: Microsoft Advisor.

## `definitions[name="OperationDisplayInfo"]/properties[name="resource"]/description`
  
Die Ressource, auf dem der Vorgang ausgeführt wird.


