# Erklärung
Dieses Script lädt eine Datei herunter und prüft den md5sum Hashwert dieser Datei.
Stimmt dieser mit einem gegebenen Wert überein, so gibt das Script eine OK Meldung aus.
Das Script verwendet die Tools cURL und md5sum.

```bash
Usage : SCRIPT -U <URL> -T <Timeout> [-h] [-v] [-V] [-b] [-W]
	-U	URL zum Downloadlink
	-T	Angabe eines Timeout Wertes in Sekunden
	-h	Zeigt diese Hilfe an
	-v	Zeigt die Version an
	-V	Sorgt für eine sehr ausführliche Ausgabe
	-b	Batchausgabe für Überwachungssysteme
	-W	Für mehr Wumms!
```

## Zabbix
Über Userparameter kann dieses Script natürlich auch in Zabbix verwendet werden.
Dafür eignet sich besonders der Parameter `-b`.
