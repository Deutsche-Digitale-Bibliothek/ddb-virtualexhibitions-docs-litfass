## D.2 Der Texteditor

Die Eingabe der Texte für die Ausstellungsseiten erfolgt in einem Texteditor (TinyMCE), der Ihnen in etwa die Formatierungsmöglichkeiten eines einfachen Textverarbeitungsprogramms bietet. 

Neben Formatierungen wie Fett- oder Kursiv-Satz erlaubt der Editor auch das Einfügen von Hyperlinks.

Der Editor steht Ihnen auch zur Verfügung, wenn Sie bei den Metadaten eines Objekts beispielsweise eine Verlinkung vornehmen möchten. Dazu setzen Sie ein Häkchen bei „HTML benutzen“ unter dem Eingabefeld.

Die Icons und Auswahl-Listen des Editors sind leicht verständlich und Ihnen wahrscheinlich aus anderen Programmen vertraut. Es folgt ein kurzer Überblick über die einzelnen Optionen.

!!!note "Formatieren Sie bitte sparsam und konsistent!"

    Die Grundformatierung Ihrer virtuellen Ausstellung übernimmt ein Template. Es sorgt dafür, dass alle Elemente gestalterisch aufeinander abgestimmt sind. Die Formatierungsmöglichkeiten des Editors sind lediglich als Ergänzung zu verstehen, um besondere Anforderungen zu erfüllen, etwa die Kursivsetzung eines im Text erwähnten Werktitels. Mit (Zwischen-)Überschriften können Sie längere Texte leserfreundlich strukturieren. Achten Sie dabei bitte darauf, dass die Überschriftenhierarchie nicht mit dem Template kollidiert und sich auf allen Seiten systematisch durchzieht.
	
##### Typografische Formatierungen

Mit dem Icon „B“ (bold) können Sie Wörter oder Textpassagen fett setzen. Bitte gehen Sie sparsam mit diesem Gestaltungsmittel um. Die Fettsetzung von Überschriften erfolgt über die Zuweisung des Überschriftenformats, bitte nicht doppelt fetten!

!![Abb. D.2-1 – Text fett setzen][D-2_1]

Das Icon „I“ (italic) setzt Text kursiv. Kursiv-Satz bietet sich bei Titeln von Werken oder Publikationen an.

!![Abb. D.2-2 – Text kursiv setzen][D-2_2]

Das Icon „Tx“ entfernt Formatierungen aus einem markierten Text. 

Die drei Icons der zweiten Sektion in der Icon-Leiste ermöglichen die Einstellung der Textausrichtung (links, zentriert, rechts).

##### Aufzählung

Mit diesem Icon können Sie Listen in Ihren Text einfügen. Die Liste wird durch Einrückungen und Listenpunkte (Bullet Points) formatiert. Das Aufzählungs-Symbol können Sie nicht verändern, da es auf Template-Ebene festgelegt ist.

Listen sind Absatzformatierungen, die Listenpunkte müssen also zunächst Absätze sein. Markieren Sie dann alle Absätze (durch „Enter“ getrennte Zeilen) und machen diese durch einen Klick auf das Listen-Icon zur Liste. Alternativ können Sie einfach den ersten Absatz als Liste formatieren – mit der Enter-Eingabe wird der folgende Absatz automatisch als Listenabsatz formatiert. Um die Listenformatierung zu entfernen, markieren Sie die gesamte Liste und klicken erneut auf das Listen-Icon.

!![Abb. D.2-3 – Aufzählung][D-2_3]

##### Nummerierte Listen

Nummerierte (sortierte) Listen unterscheiden sich von den unsortierten nur dadurch, dass an Stelle des Listenpunkts eine Ordnungszahl erscheint. Auch auf das Format der Nummerierung haben Sie keinen Einfluss.

!![Abb. D.2-4 – Nummerierte Liste][D-2_4]

##### Links einfügen

Über das Kettensymbol können Sie in Ihrem Text Hyperlinks zu beliebigen URLs oder auf andere Seiten der Ausstellung setzen. Den zu verlinkenden Text (Ankertext) schreiben Sie zunächst als gewöhnlichen Text, markieren ihn und klicken auf das Kettensymbol. Bereits verlinkte Textteile erscheinen im Backend unterstrichen. Auch die Formatierung von Links regelt das Template, Sie können sie also nicht beeinflussen.

!![Abb. D.2-5 – Links einfügen][D-2_5]

Beim Klick auf das Kettensymbol öffnet sich eine Eingabemaske, in der Sie die zur Verlinkung notwendigen Einstellungen vornehmen können. Im Feld „URL“ geben Sie zunächst das Ziel der Verlinkung ein.

Bei Links auf andere Seiten Ihrer Ausstellung setzen Sie **relative** Links. Dazu gehen Sie auf die betreffende Seite, kopieren die URL aus der Adresszeile Ihres Browsers und entfernen alles bis zu „.de“; übrig bleibt, was rechts von „.de“ steht. Ein relativer Link sieht dann beispielsweise so aus: „[$Beispiellink]“.

Bei Links auf Seiten außerhalb Ihrer Ausstellung setzen Sie **absolute** Links, die Sie direkt aus der Adresszeile Ihres Browsers übernehmen können.

Das Feld „Titel“ dient dazu, im Quellcode ein Titel-Attribut zu erzeugen. Dies ist unter anderem aus Gründen der Barrierefreiheit sinnvoll.

Das Feld „Ziel“ legt fest, ob beim Klick auf den Link ein neuer Browser-Tab geöffnet wird. Die Einstellung „Neues Fenster“ sollten Sie prinzipiell bei allen Links auswählen, die zu externen Adressen führen. So bleiben die BesucherInnen in Ihrer Ausstellung, wenn sie das aufgerufene Fenster wieder schließen.

!![Abb. D.2-6 – Dialogfenster zum Setzen eines Links][D-2_6]

Rechts neben dem Kettensymbol finden Sie das Symbol zum Entfernen eines Links. Markieren Sie den Link (oder setzen den Cursor in den Link) und klicken Sie auf das Symbol mit dem gesprengten Kettenglied, dann wird die Verlinkung entfernt.

#### Überschriften

Längere Textpassagen lesen sich leichter, wenn sie durch Zwischenüberschriften gegliedert sind. Um eine Überschrift zu setzen, schreiben Sie den Text der Überschrift in einen eigenen Absatz, markieren diesen und wählen in „Formate“ die betreffende Überschriften-Klasse aus. 

Den Überschriften sind unterschiedliche Formatierungen zugewiesen, die bereits im Schriftbild des Editors angedeutet sind. Entscheidend ist die Formatierung im Frontend. Bitte überprüfen Sie das Ergebnis Ihrer Textformatierung immer dort – das Erscheinungsbild im Backend dient nur als Anhaltspunkt.

Für Zwischenüberschriften sollten Sie eine Hierarchie-Stufe Überschrift 2-4 wählen, da die automatisch ausgegebene Seitenüberschrift das Format Überschrift 1 hat. Bitte achten Sie auf eine inhaltlich sinnvolle und konsistente Vergabe der Überschriftenformate.

Wenn Sie beim Anlegen der Seite die Option „Titel im Seiteninhalt anzeigen: nein“ gewählt haben [$QV], wird die Seitenüberschrift nicht automatisch ausgegeben. Hier können Sie eine eigene Überschrift im Format Überschrift 1 setzen.

Um eine Überschriftenformatierung zu entfernen, weisen Sie wieder das Format „Absatz“ zu.

!![Abb. D.2-7 – Zwischenüberschriften][D-2_7]

##### Zitatblock

Wenn Sie in Ihrer Ausstellung hervorgehobene Zitate einbinden möchten, steht Ihnen dazu ein eigenes Seiten-Layout zur Verfügung: „Zitatblock“ [$QV]. Sie können aber auch in einer Seite Zitatblöcke einbinden. Um einen Absatz als einen solchen Zitatblock zu gestalten, fügen Sie zunächst das Zitat mit einer kurzen Quellenangabe ein. Markieren Sie das gesamte Zitat und die Quellenangabe und wählen unter „Formate“ „blockquote“. Der betreffende Abschnitt wird im Editor eingerückt dargestellt. Nun markieren Sie die Quellenangabe und wählen in der Formate-Liste „cite“.

!!!note "Zitate-Format nur für einen Absatz geeignet"

    Das Spezialformat „blockquote“ funktioniert nur für einzelne Absätze. Auch die Quellenangabe muss innerhalb desselben Absatzes eingefügt werden. Bereits im Editor ist bei Auszeichnung des Zitatblocks das typografische Element der einseitigen eckigen Klammer angedeutet. Ihre Eingabe ist korrekt, wenn Zitat und Quelle innerhalb dieser Klammer erscheinen.

!![Abb. D.2-8 – Zitat in die Seite einbinden][D-2_8]

Nach Übernahme der Änderungen sollten Sie im Frontend schauen, ob das Zitat korrekt ausgegeben wird.

!![Abb. D.2-9 – Zitatblock in der Frontend-Darstellung][D-2_9]

##### Sonderformate große und kleine Schrift

Ebenfalls in der Auswahlliste „Formate“ stehen die Formatierungsmöglichkeiten „große Schrift“ und „kleine Schrift“ zur Verfügung.

!![Abb. D.2-10 – Sonderformate große und kleine Schrift im Frontend][D-2_10]

##### Der HTML-Modus

Die Schaltfläche „<>“ gibt Ihnen Zugang zu dem Quellcode im HTML-Format, den der Texteditor erzeugt. Wenn Sie zumindest ein wenig mit der HTML-Syntax vertraut sind, können Sie auf diese Weise im Quellcode nachschauen, falls Schwierigkeiten im normalen Editor-Modus auftauchen. 

!![Abb. D.2-11 – Der Quellcode-Editor][D-2_11]

Hier einige typische Anwendungsfälle:

* beim Kopieren aus einer Vorlage (Word, Webseite) wurden unerwünschte Formatierungen eingeschleppt
* beim Löschen von Text wurde die hierarchische Staffelung von HTML-Tags gestört, indem z.B. ein schließendes Tag versehentlich gelöscht wurde

Sie können solche Fehler im Quellcode-Editor direkt beseitigen, in aller Regel kommen Sie aber ohne den HTML-Modus aus. Wenn Sie über die nötige Expertise verfügen, kann er die Arbeit beschleunigen – notwendig ist er nicht.

##### Vollbild-Modus

Bei der Arbeit an umfangreicheren und komplexer strukturierten Texten kann es hilfreich sein, den Texteditor im Vollbildmodus zu verwenden. Sie haben dann das gesamte Browserfenster für die Arbeit am Text zur Verfügung. Klicken Sie dazu auf das letzte Icon in der Icon-Zeile (Vierpfeil-Symbol), dann schaltet der Editor in den Vollbildmodus.

!![Abb. D.2-12 – Arbeiten im Vollbild-Modus des Editors][D-2_12]

Zum Schließen der Vollbild-Ansicht klicken Sie noch einmal auf das entsprechende Icon.

[D-2_1]: img/D-2_1.jpg "Abb. D.2-1 – Text fett setzen"
[D-2_2]: img/D-2_2.jpg "Abb. D.2-2 – Text kursiv setzen"
[D-2_3]: img/D-2_3.jpg "Abb. D.2-3 – Aufzählung"
[D-2_4]: img/D-2_4.jpg "Abb. D.2-4 – Nummerierte Liste"
[D-2_5]: img/D-2_5.jpg "Abb. D.2-5 – Links einfügen"
[D-2_6]: img/D-2_6.jpg "Abb. D.2-6 – Dialogfenster zum Setzen eines Links"
[D-2_7]: img/D-2_7.jpg "Abb. D.2-7 – Zwischenüberschriften"
[D-2_8]: img/D-2_8.jpg "Abb. D.2-8 – Zitat in die Seite einbinden"
[D-2_9]: img/D-2_9.jpg "Abb. D.2-9 – Zitatblock in der Frontend-Darstellung"
[D-2_10]: img/D-2_10.jpg "Abb. D.2-10 – Sonderformate große und kleine Schrift im Frontend"
[D-2_11]: img/D-2_11.jpg "Abb. D.2-11 – Der Quellcode-Editor"
[D-2_12]: img/D-2_12.jpg "Abb. D.2-12 – Arbeiten im Vollbild-Modus des Editors"