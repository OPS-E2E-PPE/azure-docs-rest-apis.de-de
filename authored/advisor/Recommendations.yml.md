# `management.azure.com.advisor.recommendations`

## `operations[uid="management.azure.com.advisor.recommendations.generate"]/summary`
Initiiert die Empfehlung Generation oder Berechnung Prozess für ein Abonnement. Dieser Vorgang ist asynchron. Die generierten Empfehlungen werden in einem Cache im Advisor-Dienst gespeichert.

## `operations[uid="management.azure.com.advisor.recommendations.get"]/summary`
Ruft eine zwischengespeicherte Empfehlung Details ab.

## `operations[uid="management.azure.com.advisor.recommendations.getgeneratestatus"]/summary`
Ruft den Status des Prozesses Empfehlung Berechnung oder Generierung ab. Rufen Sie diese API nach dem Aufrufen der Empfehlung generieren. Der URI dieser API wird in das Feld "Speicherort" in der Antwortheader zurückgegeben.

## `operations[uid="management.azure.com.advisor.recommendations.list"]/summary`
Ruft die zwischengespeicherten Empfehlungen für ein Abonnement ab. Die Empfehlungen sind generiert oder durch Aufrufen von GenerateRecommendations berechnet.


