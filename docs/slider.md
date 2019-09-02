## C.4 Slider 

Durch Ihre Ausstellungen bewegen sich die NutzerInnen durch Scrollen – also von oben nach unten. Sie haben die Möglichkeit, die Seiten auf dieser ‚Hauptachse‘ durch weitere Inhalte zu ergänzen, die in Form eines Sliders in der Horizontalen durchblättert werden können. Für diese ergänzenden Inhalte stehen Ihnen wiederum alle in Abschnitt C.3 [$QV] vorgestellten Seiten-Layouts zur Verfügung.

Um diese in der zweiten Dimension angelegten Seiten aufzurufen, muss die Nutzerin oder der Nutzer Pfeile am unteren Bildschirmrand bedienen (oder bei touchfähigen Geräten horizontal wischen). Man sollte davon ausgehen, dass viele NutzerInnen im Fluss der dominanten vertikalen Bewegung bleiben und deshalb die weiteren Seiten nicht aufrufen. Alles, was für das Ausstellungsnarrativ wichtig ist, sollte deshalb in diesem vertikalen Hauptstrang platziert werden.

!![Abb. C.4-1 – Der Slider in im Frontend][C-4_1]

### C.4.1 Slider anlegen

Das Slider-Element ist als Container zu verstehen, in dem die horizontal anzuzeigenden Seiten angeordnet werden, der selbst aber keine Inhalte hat. Der erste Schritt zur Anlage eines Sliders ist, eine neue Seite anzulegen und ihr das Seiten-Layout Slider zuzuweisen.

!![Abb. C.4-2 – Slider durch Zuweisung des Seitenlayouts anlegen][C-4_2]

Geben Sie dem Slider-Element einen Titel, damit Sie ihn in Ihrer Seitenliste identifizieren können. Im Frontend wird dieser Titel nicht ausgegeben nicht auf der Seite ausgegeben sondern nur in der Navigation. Für die Navigation sind kurze, aussagekräftige Titel am besten geeignet. Auf die Zuweisung einer Hintergrundfarbe können Sie verzichten, da die Hintergrundfarben über die im Slider enthaltenen Seiten individuell geregelt werden.

In der Liste Ihrer Ausstellungsseiten erscheint nun ein Balken mit dem Zusatz „Anfang eines Sliders ⬇“ und einer mit dem Zusatz „Ende eines Sliders ⬆“.

!![Abb. C.4-3 – Die Seitenliste mit einem leeren Slider-Element][C-4_3]

Seiten, die zwischen diesen Rahmen-Elementen platziert werden, erscheinen im Frontend im Slider-Format.

### C.4.2 Seiten im Slider platzieren

Um den leeren Slider mit Inhalten zu befüllen, legen Sie einfach wie gewohnt Seiten an und verschieben sie anschließend in der Seitenliste per Drag & Drop zwischen die Anfangs- und Endbalken des betreffenden Sliders. Sie können jede beliebige bereits angelegte Seite in einen Slider aufnehmen (oder wieder entfernen). Die Reihenfolge in der Seitenliste bestimmt die Abfolge der Seiten im Slider.

!![Abb. C.4-4 – Die Seitenliste mit einem bestückten Slider-Element][C-4_4]

Wenn Sie Ihren Slider zusammengestellt haben, speichern Sie das Ergebnis über die Schaltfläche „Änderungen übernehmen“.

### C.4.3 Slider löschen

Das Löschen eines Sliders erfolgt – analog zum Löschen einer Seite [$QV] – durch Klick auf das „X“ im Balken. Wirksam wird das Löschen erst, wenn Sie auf die Schaltfläche „Änderungen übernehmen“ klicken. 

!![Abb. C.4-5 – Löschen eines Sliders][C-4_5]

Die im Slider platzierten Seiten werden dann wieder in die normale Seitenabfolge aufgenommen, sie gehen also durch das Löschen des Slider-Containers **nicht** verloren.

[C-4_1]: img/C-4_1.jpg "Abb. C.4-1 – Der Slider in im Frontend"
[C-4_2]: img/C-4_2.jpg "Abb. C.4-2 – Slider durch Zuweisung des Seitenlayouts anlegen"
[C-4_3]: img/C-4_3.jpg "Abb. C.4-3 – Die Seitenliste mit einem leeren Slider-Element"
[C-4_4]: img/C-4_4.jpg "Abb. C.4-4 – Die Seitenliste mit einem bestückten Slider-Element"
[C-4_5]: img/C-4_5.jpg "Abb. C.4-5 – Löschen eines Sliders"