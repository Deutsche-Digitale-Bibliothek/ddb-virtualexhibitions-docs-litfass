## D.3 Mediendateien

DDBStudio bietet Ihnen die Möglichkeit, die ‚Exponate‘ auf attraktive Weise online zu präsentieren. Die Qualität der Präsentation hängt wesentlich auch von der (technischen) Qualität der Digitalisate ab, die Sie in Ihre Ausstellung einbinden.

Wie bei jedem Online-Medium, das unter den unterschiedlichsten Bedingungen genutzt wird – mit einem Breitbandanschluss, über WLAN, von einem Mobilgerät aus ... –, ist allerdings auch der Umstand, wie schnell die Seiten laden, ein wesentlicher Faktor für eine gelungenes Erlebnis der Nutzer*innen Ihrer Ausstellung.

Die beiden Anforderungen stehen notgedrungen in einer gewissen Konkurrenz zueinander: Hochauflösende, großformatige Bilder garantieren brillante, unverfälschte Darstellungen und lassen sich bis in die kleinsten Details heranzoomen. Aber sie führen eben auch zu längeren Ladezeiten und strapazieren u.U. die Geduld der Nutzer*innen. 

Es gilt also, die beiden Anforderungen zu einem optimalen Ausgleich zu bringen. Im Folgenden haben wir einige Hinweise zusammengestellt, die Ihnen dabei helfen können.

### D.3.1 Sinnvolle Bildgrößen

Wenn Sie ein Bild nur als Seitenhintergrund verwenden ([siehe Abschnitt C.3.2](seiten_layouts.html#layout-2-nur-objekt)) verwendet DDBstudio ein beim Dateiupload erzeugte Version, die in ihrer Größe dieser Funktion angepasst ist. Auch die Abbildungen auf den Seiten mit Text-Bild-Kombination sind in der Größe entsprechend optimiert.

Das Bild in seiner vollen Auflösung ist erst bei Aufruf des Zoom-Tools über das Lupensymbol zu sehen. Hier liegt eine besondere Stärke des digitalen Mediums: Man kann die Objekte in einer Detailliertheit sehen, die oft nicht einmal bei der Präsentation des realen Objekts in einer Ausstellung möglich ist. Welcher Grad der Nahsichtigkeit inhaltlich noch Sinn ergibt, können Sie aus Ihrer kuratorischen Sicht sicherlich am besten entscheiden. Die Größe des eingebundenen Bildes auf dieses inhaltlich sinnvolle Maß zu beschränken, kann zu erheblich schnelleren Ladezeiten führen.

!!!note "Ränder und Umraum"

    Oft kann ein etwas knapperer Beschnitt der Digitalisate zu erheblich kleineren Dateigrößen führen. Gelingt es, am Rand etwas wegzulassen, was für die Darstellung des Objekts ohne Belang ist (neutraler Hintergrund, Ränder, ...) wirkt sich dies überproportional auf die Dateigröße aus, weil auch schmale Randstreifen große Flächen einnehmen.

### D.3.2 Bildkompression

DDBstudio akzeptiert komprimierte Bilddateien in den Formaten .jpg oder .png. Welche Kompressionsstufe Sie bei .jpg-Dateien wählen können, ohne nennenswerte Qualitätseinbußen hinnehmen zu müssen, hängt stark vom Motiv und der grafischen Struktur des Digitalisats ab. Im Hinblick auf kurze Ladezeiten möchten wir Sie ermuntern, die Grenzen sorgfältig auszuloten.

Wesentlich bessere Ergebnisse als mit Standardprogrammen wie Photoshop oder Gimp erzielen Sie bei der Bildkompression, wenn Sie eigens auf diese Aufgabe spezialisierte Tools einsetzen. Unter anderem die folgenden Dienste könnten Sie dazu einsetzen:

#### Online-Service jpeg.io

Die Website [jpeg.io](https://www.jpeg.io){target=_blank} bietet Ihnen die Möglichkeit, unkompliziert Bilddateien unterschiedlichster Formate in gut komprimierte .jpg-Dateien zu konvertieren. Ziehen Sie dazu einfach die zu bearbeitenden Dateien in das Uploadfeld (oder klicken Sie auf dieses und markieren die Dateien im Auswahlfenster). Alternativ steht der Import von Dropbox, Google Drive oder Box zur Verfügung. Die konvertierten Dateien können Sie am Ende als Zip-Datei herunterladen.

Der Service verarbeitet Dateien bis 50 MB. Wenn Ihre Ausgangsdateien größer sind, müssten Sie diese zunächst vorbearbeiten.

!![Abb. D.3-1 - Online-Service jpeg.io][D-3_1]

#### Online-Service squoosh.app

Auch der Service [squoosh.app](https://squoosh.app/){target=_blank} bietet die relativ unkomplizierte Online-Kompression an, allerdings muss man hier Bild für Bild vorgehen und sieht sich mit einem Upload-Limit von 16 MB pro Bild konfrontiert. Gegenüber jpeg.io bietet squoosh.app zwei Vorteile: Die Kompressionseinstellungen lassen sich nach dem Upload justieren und das Ergebnis der Kompression ist in Echtzeit zu sehen, mit einem praktischen Schieber, mit dem Sie Original und komprimierte Version an jeder Stelle direkt vergleichen können. Schon deshalb ist die Seite ein guter Einstieg, um sich anschaulich mit dem Thema Bildkompression auseinander zu setzen.

!![Abb. D.3-2 - Online-Service squoosh.app][D-3_2]

#### Für Versierte: Das Commandline-Tool jpeg-archive/jpeg-recompress

Wenn Sie versiert im Umgang mit Tools und Skripten sind, die über die Kommandozeile bedient werden, sollten Sie die Verwendung des Tools [jpeg-archive](https://github.com/danielgtaylor/jpeg-archive){target=_blank} in Erwägung ziehen. Es arbeitet mit dem Skript jpeg-recompress, das bei der Bildkompression sonst kaum zu erreichende Ergebnisse erzielt, mit substantiell reduzierten Dateigrößen bei mit bloßem Auge kaum wahrnehmbaren Qualitätseinbußen.

Am wenigsten technischen Aufwand erfordert der Download der Binaries und die lokale Komprimierung von Arbeitskopien der Bilddateien (die durch die komprimierte Version erstetzt werden) Datei für Datei. Nach unseren Tests war die [Version 2.1.1](https://github.com/danielgtaylor/jpeg-archive/releases/tag/2.1.1){target=_blank} der letzte voll funktionsfähige Release (Stand: Juni 2019).

Zu den zahlreichen Möglichkeiten, den Kompressionsvorgang zu konfigurieren, mit mehreren Dateien und Ordnern zu arbeiten etc. siehe die ausführliche Dokumentation bei [GitHub](https://github.com/danielgtaylor/jpeg-archive){target=_blank}. 

[D-3_1]: img/D-3_1.jpg "Abb. D.3-1 - Online-Service jpeg.io"
[D-3_2]: img/D-3_2.jpg "Abb. D.3-2 - Online-Service squoosh.app"