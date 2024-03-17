Dieses Python-Skript dient dazu, Informationen über den Sonnenaufgang, den Sonnenuntergang und die Dauer des Tageslichts für eine bestimmte Stadt in Deutschland von der Website "timeanddate.de" zu erhalten

Es importiert die erforderlichen Module BeautifulSoup und requests, um Webseiteninhalte abzurufen und zu analysieren.

Die Funktion umlaut_convert(text) wandelt Umlaute (ä, ö, ü, Ä, Ö, Ü) in ASCII-äquivalente Zeichen (ae, oe, ue, Ae, Oe, Ue) um. Dadurch wird sichergestellt, dass der Stadtnamen korrekt verarbeitet werden kann.

Es gibt drei Hauptfunktionen:

sunrise(city): Diese Funktion ruft die Sonnenaufgangszeit für die angegebene Stadt ab, indem sie die Webseite für die entsprechende Stadt aufruft und die Zeit extrahiert.

sunset(city): Diese Funktion ruft die Sonnenuntergangszeit für die angegebene Stadt ab, indem sie die Webseite für die entsprechende Stadt aufruft und die Zeit extrahiert.

day_light(city): Diese Funktion ruft die Tageslichtdauer für die angegebene Stadt ab, indem sie die Webseite für die entsprechende Stadt aufruft und die Dauer extrahiert.

Die Funktionen werden mit dem eingegebenen Stadtnamen aufgerufen, um die entsprechenden Daten abzurufen.

Es gibt drei Hauptfunktionen:

Der Benutzer wird aufgefordert, den Namen der Stadt einzugeben.
