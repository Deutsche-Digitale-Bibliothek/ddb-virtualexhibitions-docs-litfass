## B.4 Das Objekt mit Medien-Dateien verknüpfen

### B.4.1 Verknüpfen mit einer Bild-Datei

Um das Objekt mit einer Mediendatei – dem Digitalisat des Objekts, das Sie in der Ausstellung präsentieren möchten – zu verknüpfen, wechseln Sie von der Eingabemaske für die Metadaten [$QV] auf den Reiter „Dateien“.

!![Abb. B.4-1 – Reiter „Dateien“ auf der Seite „Objekt … bearbeiten“][B-4_1]

Über die Schaltfläche „Datei auswählen“ wählen Sie eine Datei von der Festplatte Ihres Computers für den Upload aus. Wenn Sie im Dialogfenster die Auswahl bestätigt haben, erscheint der Dateiname neben der Schaltfläche. 

!!! note "Zulässige Formate für Bild-Dateien"

    Bitte beachten Sie im Eingabefeld „Neue Dateien hinzufügen“ die Hinweise zu den zulässigen Dateiformaten. Dies sind:

    * .jpg (Joint Photographic Experts Group)
    * .png (Portable Network Graphics)
    * .gif (Graphics Interchange Format)

    Dateien in unkomprimierten Formaten (z.B. .tiff) konvertieren Sie bitte vor dem Upload in .jpg oder .png. 
    
    PDF-Dateien können nicht zur Repräsentation des Objekts verwendet werden.

Auf den Ausstellungsseiten steht für die eingebundenen Bilder später ein Zoomtool zur Verfügung. Die NutzerInnen können die Bilder vergrößern, bis die native Auflösung des eingestellten Bildes erreicht ist, also bis ein Pixel des Bildes einem Pixel in der Frontend-Ausgabe entspricht. Wenn Sie Ihren BesucherInnen diese Möglichkeit bieten wollen, sollten Sie ausreichend große, d.h. hochaufgelöste Bilder verwenden. Für die Ausgabe im Kontext der Seite, also im ungezoomten Zustand, verwendet DDBstudio ein Vorschaubild in reduzierter Größe. Das Einstellen großer, hochauflösender Bilder verlangsamt also den Aufruf der eigentlichen Ausstellungsseiten nicht, soweit es sich um Text-Bild-Kombinationen handelt. Siehe auch den Abschnitt „Sinnvolle Bildgrößen“ im Anhang. [$QV]

Zoombarkeit ist aber auch kein Selbstzweck. Wenn Sie etwa als Archivdokument ein Typoskript präsentieren, trägt es wahrscheinlich zum Ausstellungserlebnis wenig bei, wenn man es so weit heranzoomen kann, dass die Holzfasern im Papier erkennbar werden. Verstehen Sie die Zoomfunktion als Gestaltungselement, das Sie im Sinne Ihrer kuratorischen Konzeption einsetzen können (aber nicht müssen). Wurden keine Einstellungen vorgenommen, wird ein Zoomausschnitt mit hoher Zoomstufe sowie vertikler und horizontaler Zentrierung erzeugt.     

!!! note "Transparente Hintergründe und Animationen"

    Gerade im Design von DDBstudio mit den abgestimmten farbigen Hintergründen können Sie sehr schöne Effekte mit freigestellten Objektbildern erzielen, also mit Darstellungen, bei denen der Hintergrund eine Alphatransparenz aufweist. Möglich ist dies in den Formaten .png und .gif. Für hochauflösende Bilder mit nuancierter Farbigkeit sollten Sie .png-Bilder verwenden.

    Auch animierte .gif-Bilder können Ihre Ausstellung beleben. Gedacht ist dieses Format allerdings für sehr kurze, in Endlosschleife laufende Animationen. Wenn die Bewegtbildabfolge komplexer und länger wird, empfehlen wir, ‚richtige‘ Videos einzusetzen. Sie sind dafür besser geeignet, bieten den NutzerInnen die Möglichkeit, die Wiedergabe zu kontrollieren und werden gestreamt, nicht auf einmal geladen. Längere .gif-Animationen werden schnell sehr groß, was die Datenmenge angeht.

Nachdem Sie die Änderungen übernommen haben, wird die verknüpfte Datei auf den Server geladen (was bei größeren Dateien einige Zeit dauern kann) und anschließend auf der Objektseite als Vorschaubild angezeigt.  Wenn Sie nun wieder in den Modus „Bearbeiten“ und dort zum Reiter „Dateien“ wechseln, erscheint der Name der verknüpften Datei in einem Balken mit Textlink zum Löschen der Datei. Auch das Löschen wird erst beim Speichern des Objekts wirksam.

!!! note "Datei löschen ist nicht gleich Objekt löschen"

    Wenn Sie eine verknüpfte Datei löschen möchten, klicken Sie bitte auf den Textlink „Löschen“ (neben „Bearbeiten“) und nicht auf die Schaltfläche „Löschen“ im Kasten rechts – diese löscht das ganze **Objekt**, nicht nur die Datei!

!![Abb. B.4-2 – Reiter „Dateien“ mit eingestelltem Objekt][B-4_2]

### B.4.2 Verknüpfen mit einer Audio-Datei

Wenn es sich bei Ihrem ‚Exponat‘ um eine Tonaufnahme handelt, funktioniert die Einbindung der entsprechenden Datei (zulässige Audio-Formate sind .mp3 und .ogg) analog zur Einbindung einer Bild-Datei [$QV]. In der Ausstellung wird die Datei über einen Player wiedergegeben. Damit Ihre BesucherInnen beim Anhören nicht nur die nüchterne Bedienoberfläche des Players vor Augen haben, können Sie ein Bild als weitere Datei einbinden, die dann über dem Player angezeigt wird. Bitte binden Sie genau **eine** Audio-Datei und ggf. **ein** Bild ein. 

### B.4.3 Verknüpfen mit einer Video-Datei

Aus technischen Gründen werden Videos nicht als Dateien eingebunden, sondern über die Verlinkung mit einer Plattform zum Video-Streaming. Diese erfolgt über ein Metadatenfeld (also im Reiter „Metadaten“, nicht „Dateien“). Sie können Videos aus der Deutschen Digitalen Bibliothek oder von Vimeo nutzen. Den Shortcode, der im Feld „Videoquelle“ eingetragen wird, um die Verknüpfung zur entsprechenden Plattform zu erzeugen, können Sie bequem über die grüne Schaltfläche „Video-Shortcode-Helfer“ erzeugen. 

!![Abb. B.4-3 – Dialogbox „Video-Shortcode-Helfer“][B-4_3]

Hier wählen Sie zunächst die Videoplattform aus, dann die ID des Videos auf der betreffenden Plattform. Die ID können Sie auf Vimeo über den Button „Teilen“ abrufen. Tragen Sie bitte nur die ID selbst in das Feld ein, nicht die Domain der Plattform (also **ohne** https://vimeo.com/). Wenn Sie ein Video aus der Deutschen Digitalen Bibliothek verwenden, rufen Sie das betreffende Objekt in der DDB auf und kopieren die ID aus der URL der Seite (aus der Adresszeile oder über „Link auf diese Seite“); es handelt sich um die Zeichenfolge hinter „.../item/“.

Das Video [Des Jägers Traum (1903)](https://www.deutsche-digitale-bibliothek.de/item/Q2AYVOWHLQMIGAXOTNAPWAE4CCJLAW6U), das auf dem DDB-Portal unter der URL https://www.deutsche-digitale-bibliothek.de/item/Q2AYVOWHLQMIGAXOTNAPWAE4CCJLAW6U verzeichnet ist, kann also über den Eintrag Q2AYVOWHLQMIGAXOTNAPWAE4CCJLAW6U im Feld „Video-ID“ in eine Ausstellung eingebunden werden.

Wenn die Video-Quelle die DDB ist, können Sie über die Felder „Startzeit“ und „Stoppzeit“ festlegen, dass in der Ausstellung nur eine bestimmte Sequenz aus dem Video abgespielt wird. Mit „Übernehmen“ bestätigen Sie Ihre Eingaben, gespeichert werden sie erst beim Speichern des Objekts.

### B.4.4 Mehrseitige Objekte zum Durchblättern im Bookviewer

Auf den Seiten Ihrer Ausstellung wird immer nur ein Digitalisat ausgegeben. Wenn Sie eine Serie von Objekten präsentieren möchten, können Sie für jedes Objekt eine Seite anlegen und ggf. das Slider-Modul nutzen [$QV]. 

Bei bestimmten Objekten, besonders mehrseitigen Publikationen, Heften etc., können Sie eine Präsentation in einem Bookviewer verwenden, der außerhalb der Ausstellung aufgerufen wird. Er dient deshalb eher der vertiefenden Beschäftigung mit dem Material und ist nicht mehr integraler Bestandteil der Ausstellung.

Die Einbindung des Bookviewers erfordert auf Objektebene lediglich, dass Sie die Bestandteile (z. B. die Seiten eines Buchs) in der richtigen Reihenfolge nacheinander als einzelne Bild-Dateien einbinden.

!![Abb. B.4-4 – Mehrere Bild-Dateien einbinden][B-4_4]

Ein Klick auf die grüne Schaltfläche „Weitere Datei hinzufügen“ erzeugt einen neuen Button „Datei auswählen“. Mit dem Speichern des Objekts wird die Serie der so eingebundenen Dateien hochgeladen. Wenn Sie anschließend das Objekt bearbeiten und wieder zum Reiter „Dateien“ wechseln, erscheint jede Datei in einem eigenen Balken. Die Balken können per Drag & Drop verschoben werden, falls Sie die Reihenfolge korrigieren möchten.

!![Abb. B.4-5 – Darstellung der eingebundenen Dateien als verschiebbare Balken][B-4_5]

Auch diese Änderungen werden erst wirksam, wenn Sie das Objekt speichern („Änderungen übernehmen“).

Auf der Übersichtsseite zum Objekt erscheint in der rechten Spalte ein Bookviewer-Link. Diesen können Sie in Ihrer Ausstellung als relativen Textlink verwenden, um den BesucherInnen Zugang zum Bookviewer zu geben. Bitte wählen Sie die für „Ziel“ die Option „Neues Fenster“, damit die NutzerInnen beim Schließen des Bookviewerfensters wieder an der ursprünglichen Stelle in der Ausstellung landen. Wenn Sie auf den Link „anzeigen“ in der Box „Bookviewer-Link“ klicken, können Sie von der Übersichtsseite den Bookviewer zu diesem Objekt direkt aufrufen.

Sie können nun noch die Darstellungsoptionen im Viewer ändern, indem Sie beim Einbinden in die Ausstellung bei dem Bookviewer-Link die Parameter „n0“ und „2up“ ändern. Die Zahl hinter „n“ schlägt initial die entsprechende Seite auf, also „n1“ die Seite 2 der Folge (die Zählung beginnt mit 0), „n5“ die Seite 6 usw. Analog dazu zeigt „1up“ Einzelseiten, „2up“ jeweils zwei Seiten usw.

### B.4.5 3D-Objekte einbinden

Neben Bildern, Audio-Dateien und Videos können Sie auch 3D-Objekte im Format X3D in Ihre Ausstellung einbinden. Ein Beispiel finden Sie in der $Musterausstellung ...

Für das Anlegen von 3D-Objekten steht auf der Seite „Objekt # ... bearbeiten“ ein eigener Reiter zur Verfügung. 

!![Abb. B.4-6 – Anlegen eines 3D-Objekts][B-4_6]

Es werden drei Komponenten benötigt:

* eine .X3D-Datei als räumliches Modell
* eine .jpg-Datei als Textur
* ein Vorschaubild

Über die drei Schaltflächen „Datei auswählen“ wählen Sie die entsprechenden Dateien auf Ihrer Festplatte aus. Wie bei Bild- und Audio-Dateien erfolgt der Upload beim Speichern des Objekts („Änderungen übernehmen“).

Wenn Sie den Reiter „3D-Dateien“ für dieses Objekt erneut aufrufen, sehen Sie die beiden 3D-Dateien und das Vorschaubild in der Box „Aktuelle 3D-Dateien“ aufgeführt. Wenn Sie andere Dateien einbinden möchten, entfernen Sie bitte die vorhandenen zunächst, indem Sie ein Häkchen bei „Aktuelle 3D-Dateien löschen“ setzen und die Änderungen übernehmen.

!![Abb. B.4_7 – Reiter „3D-Dateien“ mit eingestelltem 3D-Objekt][B-4_7]

Damit steht Ihnen das 3D-Objekt zur Verwendung in der Ausstellung zur Verfügung. Um zu überprüfen, ob die 3D-Darstellung wie gewünscht funktioniert, rufen Sie das Objekt am besten über die Schaltfläche „Seite anzeigen“ auf der DDB-Objekt-Detailseite auf.



[B-4_1]: img/B-4_1.jpg "Abb. B.4-1 – Reiter „Dateien“ auf der Seite „Objekt … bearbeiten“"
[B-4_2]: img/B-4_2.jpg "Abb. B.4-2 – Reiter „Dateien“ mit eingestelltem Objekt“"
[B-4_3]: img/B-4_3.jpg "Abb. B.4-3 – Dialogbox „Video-Shortcode-Helfer“"
[B-4_4]: img/B-4_4.jpg "Abb. B.4-4 – Mehrere Bild-Dateien einbinden"
[B-4_5]: img/B-4_5.jpg "Abb. B.4-5 – Darstellung der eingebundenen Dateien als verschiebbare Balken"
[B-4_6]: img/B-4_6.jpg "Abb. B.4-6 – Anlegen eines 3D-Objekts"
[B-4_7]: img/B-4_7.jpg "Abb. B.4_7 – Reiter „3D-Dateien“ mit eingestelltem 3D-Objekt"
