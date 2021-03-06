# Scriptschritte

Scriptschritte werden unter [Aufgabendetails](Bearbeitung-Aufgabe.md) definiert.

Dies erfolgt, wenn eine [Aufgabe](Aufgaben.md) nicht direkt von Kitodo.Production durchgeführt werden kann. Zum Beispiel kann dies eine eine OCR-Anbindung sein, in der die OCR zwar von einem anderen Programm durchgeführt wird, der Datentransfer jedoch automatisch erfolgen soll. Mit einem Kommandozeilenaufruf lässt sich das Script auslösen.

Es gibt zwei Möglichkeiten, das Script auszulösen:

* automatisch
* manuell

Bei der ersten Möglichkeit wird die Aufgabe (und damit das Script) automatisch mit Abschluss der vorigen Aufgabe ausgeführt. Bei der zweiten Möglichkeit wird die Aufgabe übernommen und das Script-Icon manuell angeklickt.

**ACHTUNG**: Auch wenn das Script manuell ausgelöst wird, kann die Aufgabe, die dahinter liegt (zum Beispiel der Datentransfer zur OCR) automatisch ausgeführt werden.

# Weitere Informationen
* Tutorial: [Produktionsvorlage anlegen und Workflow definieren](https://github.com/kitodo/kitodo-tutorials/blob/master/kitodo2/04_produktionsvorlage-anlegen-und-workflow-definieren.md)
* Anwenderdokumentation: [Aufgabendetails](Bearbeitung-Aufgabe.md)