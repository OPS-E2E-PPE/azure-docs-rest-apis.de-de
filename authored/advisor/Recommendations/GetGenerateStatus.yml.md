# `management.azure.com.advisor.recommendations.getgeneratestatus`

## `summary`
Ruft den Status des Prozesses Empfehlung Berechnung oder Generierung ab. Rufen Sie diese API nach dem Aufrufen der Empfehlung generieren. Der URI dieser API wird in das Feld "Speicherort" in der Antwortheader zurückgegeben.

## `uriParameters[name="subscriptionId"]/description`
Die Azure-Abonnement-ID.

## `uriParameters[name="operationId"]/description`
Die Vorgangs-ID, die im Antwortheader generieren Empfehlung aus dem Feld "Speicherort" befinden.

## `uriParameters[name="api-version"]/description`
Die Version der API mit der Clientanforderung verwendet werden soll.

## `responses[name="202 Accepted"]/description`
Akzeptiert. Generierung der Empfehlung wird ausgeführt.

## `responses[name="204 No Content"]/description`
NoContent. Empfehlung Generierung wurde abgeschlossen.


