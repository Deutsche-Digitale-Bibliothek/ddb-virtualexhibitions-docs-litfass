## D.1 Metadaten

Das Metadatenschema für die Objekte Ihrer Ausstellung ist so ausgelegt, dass ein breites Spektrum an Medientypen abgedeckt ist. Im Zusammenhang der virtuellen Ausstellungen haben die Metadaten in erster Linie eine deskriptive Funktion: Sie sollen über das im Rahmen der Ausstellung gezeigte Objekt informieren – die inhaltserschließende Funktion spielt hier eine untergeordnete Rolle. Sie können deshalb die Metadatenfelder relativ frei befüllen, ohne an ein vorgegebenes Schema für die Datenerfassung gebunden zu sein. Priorität hat die Lesbarkeit und Verständlichkeit aus Sicht des Publikums.

Die meisten Metadaten werden im Frontend der Ausstellung ausgegeben, manche dienen auch nur technischen Zwecken wie der Verknüpfung mit einer Datenquelle. Angezeigt werden Metadaten nicht direkt auf den Ausstellungs-Seiten selbst, sondern in einer Info-Box, die durch Klick auf das „i“-Icon geöffnet wird. 

!![Abb. D.1-1 – Infobox mit Metadaten zu einem Objekt][D-1_1]

Außerdem erscheinen die Metadaten auf der Detailseite zum Objekt, sofern es sich um ein Objekt handelt, das nicht in der DDB vorhanden ist. In diesem Fall gelangt man über den Link „Zum Objekt >>“ zur Seite des Objekts in der DDB, wo es mit den beim Ingest des Objekts eingespielten Metadaten ausgegeben wird.

!!! note "Wenn Sie DDB-Objekte verwenden, müssen Sie nur wenige Metadaten eingeben"

    Wenn die Objekte Ihrer Ausstellung bereits in der DDB verfügbar sind, können Sie sich bei der Eingabe der Metadaten auf die wenigen Felder beschränken, die in der Info-Box ausgegeben werden. Denn das Objekt hat in diesem Fall keine eigene Detailseite im Ausstellungskontext.

    Sollte es vorkommen, dass die in der DDB eingepflegten Metadaten nicht korrekt oder vollständig sind, und es ist für Ihre Ausstellung wichtig, andere oder zusätzliche Daten auszugeben, entfernen Sie den Link zum Objekt in der DDB und geben diese Daten in Omeka ein.

!![Abb. D.1-2 – Detailseite zu einem Objekt mit Metadatenausgabe][D-1_2]

Nicht ausgefüllte Metadatenfelder werden bei der Ausgabe ignoriert, es entstehen also keine Lücken. Die für die Ausgabe in der Info-Box vorgesehenen Felder sollten ausgefüllt werden. Pflichtfelder sind mit einem * gekennzeichnet; wenn Sie diese Felder nicht ausfüllen, erhalten Sie beim Speichern des Objekts eine Fehlermeldung.

##### Titel*

Der Titel des Objekts  

**Ausgabe**: Info-Box, Objekt-Detailseite (als Titel der Seite)

##### Weiterer Titel

z. B. Untertitel, Originaltitel in anderer Sprache, gleichwertiger Titel, ursprünglicher Titel (z. B. Mona Lisa/La Joconde).

**Ausgabe**: Objekt-Detailseite

##### Beschreibung

Ausführliche Beschreibung des Objekts  

**Ausgabe**: Objekt-Detailseite

##### Kurzbeschreibung

Kurze Beschreibung des Objekts 

**Ausgabe**: Info-Box, Objekt-Detailseite

##### Name der Institution*

Offizielle Bezeichnung der Institution, die das Objekt besitzt 

**Ausgabe**: Info-Box, Objekt-Detailseite („Aus der Sammlung von“)

##### URL der Institution

Internet-Präsenz der Institution, die das Objekt besitzt 

**Ausgabe**: als Ziel hinter dem verlinkten Namen der Institution: Info-Box, Objekt-Detailseite

##### Link zum Objekt in der DDB

URL des Objekts im Portal der DDB. **Wichtig:** Die korrekte URL erhalten Sie nur, indem Sie das Objekt in der Deutschen Digitalen Bibliothek aufrufen und dort auf der Objektseite auf den Link „Link auf diese Seite“ klicken, der direkt über dem Titel des Objekts zu finden ist 

**Ausgabe**: Info-Box, als Linkziel von „Zum Objekt >>“ (Wenn kein Link zum Objekt in der DDB vorhanden ist, führt dieser Link zur Detailseite.)

##### Link zum Objekt bei der datengebenden Institution

URL des Objekts in der Datenbank oder auf der Website der Institution, die das Objekt besitzt 

**Ausgabe**: Objekt-Detailseite 

**Anmerkung**: Bitte **nur** dann ausfüllen, wenn das Objekt **nicht** in der Deutschen Digitalen Bibliothek zu finden ist. Andernfalls unbedingt leer lassen!

##### Rechtsstatus*

Hier die Copyrightangaben passend zum Rechtsstatus angeben 

**Ausgabe**  Info-Box („Wie darf ich das Objekt nutzen?“), Objekt-Detailseite („Rechtsstatus“), jeweils als Linkziel der zur Lizenz passenden Piktogramme

##### Copyright

Angabe von Lizenz- oder Rechtehinweis; die Eingabe erfolgt über eine Auswahl-Liste 

**Ausgabe** Info-Box („Quelle“), Objekt-Detailseite

##### Typ

Die Art des Objekts (z. B. Gemälde, Fotografie, Buch ...) 

**Ausgabe**: Objekt-Detailseite  

##### Teil von

Zugehörigkeit zu einem übergeordneten Werkzusammenhang (z. B. erschienen in ..., Band 3 der Reihe ...) 

**Ausgabe**: Objekt-Detailseite

##### Thema

Thema, Kontext, Indexbegriff, Ort ... 

**Ausgabe**: Objekt-Detailseite

##### Beteiligte Personen und Organisationen

Personen, die an der Herstellung des Objekts beteiligt waren, etwa als AutorIn, HerstellerIn, ... 

**Ausgabe**: Objekt-Detailseite

##### Zeit

Zeitangabe zur Herstellung, zur Laufzeit, Erscheinungsdatum ... 

**Ausgabe**: Objekt-Detailseite

##### Ort

Herstellungs- oder Erscheinungsort, historische Bezeichnung des Orts, wenn der im Titel genannte Ort nicht der tatsächlich dargestellte Ort ist ... 

**Ausgabe**: Objekt-Detailseite

##### Maße/Umfang

Die für das Objekt passenden Angaben zur Dimension: Abmessungen, Seitenzahl, Länge von Ton- oder Filmaufnahmen, ... 

**Ausgabe**: Objekt-Detailseite

##### Material/Technik

Angaben zum verwendeten Material und zur Technik, z. B. Öl auf Leinwand, Holz, Grisaille, mp3, ... 

**Ausgabe**: Objekt-Detailseite

##### Sprache

Bei textuellen Objekten die Sprache, in der der Text verfasst ist, ggf. Angaben zur Übersetzung oder Originalsprache 

**Ausgabe**: Objekt-Detailseite

##### Identifikator

Information, die nötig ist, um das Objekt im Bestand der datengebenden Institution zu finden: Signatur, Inventarnummer, ... 

**Ausgabe**: Objekt-Detailseite

##### Anmerkungen

Feld für interne Vermerke, besonders zum Bearbeitungsstand 

**Ausgabe**: wird im Frontend nicht ausgegeben

##### Förderung

Fördermittelgeber, Förderprogramm 

**Ausgabe**: Objekt-Detailseite

##### Videoquelle

Dieses Feld dient zur Verknüpfung mit einem Video, siehe Abschnitt [$QV objekte_medien.md] 

**Ausgabe**: als Video in einem Player (Ausstellungseite und Objekt-Detailseite)

[D-1_1]: img/D-1_1.jpg "Abb. D.1-1 – Infobox mit Metadaten zu einem Objekt"
[D-1_2]: img/C-1_2.jpg "Abb. D.1-2 – Detailseite zu einem Objekt mit Metadatenausgabe"