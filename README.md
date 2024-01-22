# Wickelmaschine

### Die Entwicklung und Konstruktion, sowie die Herstellung des Prototyps erfolgte im Rahnen einer Masterarbeit an der Hochschule Osnabrück.

Mit dieser Wickelmaschine können faserverstärkte Rohre z.B. (CFK o. GFK) hergestellt werden. Die Abmessungen der Rohre können nach individuellen Wünschen gestaltet werden und können u.a. für Sport und Campingequipment verwendet werden. Die Maschine arbeitet nach dem Tapelege- oder Tapewickelverfahren, bei dem unidirektional verstärkte Kunststofftapes um den Kern gewickelt und durch eine Wärmequelle mit den unteren Schichten verbunden werden.

![Wickelmaschine](https://github.com/Simon0613/Wickelmaschine/assets/149043603/025445cb-805b-4898-ba74-c6d502e7f791)




Die Wickelmaschine kann mit einfachen Fertigungsverfahren hergestellt werden. Der größte Teil der Bauteile kann mit einem FDM-3D-Drucker angefertigt werden. Weiterhin werden Normteile wie Schrauben, Lager, Einschmelzmuttern und Federn verwendet. Für den Antrieb der Achsen werden Komponenten verwendet die sich in vielen 3D-Druckern wiederfinden: Schrittmotoren, GT2- Riemen und Riemenscheiben, Arduino Uno, CNC-Shield usw.  Der Rest besteht aus Halbzeugen wie Rohren und Flachprofile, die zugesägt, gebohrt und ein wenig gefeilt werden müssen. 

![Prototyp](https://github.com/Simon0613/Winding-Machine/assets/149043603/dafd721c-6806-4b19-a8d1-21fb84db15fe)

Die Dimensionen der Rohre können nach persönlichen Anforderungen gestalltet werden. Die Maschine kann Rohre mit einen Durchmesser von 15-55 mm herstellen. Die Länge der Rohre ist beliebig einstellbar, nur die Wickelmaschine muss im vorhinein auf die gewünschten Rohrlängen passend angefertigt sein.

![3RohreUnterschiedliche Teilung](https://github.com/Simon0613/Winding-Machine/assets/149043603/0af7add4-4a20-4e76-a316-02c705d3e2a4)
![Nahaufnahme](https://github.com/Simon0613/Winding-Machine/assets/149043603/f596b2fa-aa4a-4fbd-bd2a-50b659092b6b)
![Überblick Rohre](https://github.com/Simon0613/Winding-Machine/assets/149043603/d6790a5b-0d75-4a49-9b65-486a5ddf13c2)

![LizenzOSH](https://github.com/Simon0613/Wickelmaschine/assets/149043603/33c6dd5d-a7cb-4ab0-9db5-cbd49b78156b)


# Montageanleitung

### Folgendes Werkzeug wird für den Bau der Anlage benötigt:

- Bohrmaschine
- Werkzeug zum Anzeichnen der Bohrungen
- Flachfeile
- 3,3 mm Bohrer
- 4,5 mm Bohrer
- M4 Gewindeschneider
- Kegelsenker
- Stirnsenker für M4 Zylinderschrauben
- Lötkolben
- Maßband
- Säge
- Reiniger
- Innensechskantschlüsselsatz


### Aufbauanleitung
Nachdem alle Bauteile entsprechend der Stückliste besorgt wurden, kann mit dem Bauteilzuschnitt begonnen werden. Dazu werden die Rohre entsprechend der Zeichnung_Wellenzuschnitt abgelängt. Die Rohre mit der Bezeichnung T005_Führungsrohr und T060_Kern können je nach persönlichem Wunsch auf eine individuelle Länge abgelängt werden. Sollte der Wunsch bestehen eine Anlage für längere Rohre zu bauen. Die Wellen und Achsen können ebenfalls nach der Zeichnung_Wellenzuschnitt abgelängt werden. Es wird empfohlen die Rohr- und Wellenenden zu entgraten, um sie später besser montieren zu können.
Die Bauteile, die gedruckt werden müssen, sind in folgender Tabelle mit der benötigten Stückzahl gekennzeichnet. Zusätzlich können der Tabelle die Druckeinstellungen für die 3D-Druckteile entnommen werden. Einige Bauteile sind mit „Optional“ markiert, die nur gedruckt werden müssen, sobald ein Material oder eine andere Düse verwendet wird.

1. Zusammenbau der Baugruppe B02_Tapeklemme.
2. 2-mal Zusammenbau Baugruppe B03_Führungswagen.
3. Zusammenbau Baugruppe B05_Grundaufbau_links.
4. Die Baugruppen B03_Führungswagen werden auf die beiden Rohre T005_Führungsrohr aufgeschoben.
5. Die Baugruppen B03_Führungswagen werden mit dem Bauteil T022_Grundplatten mit 12 Innensechskantschrauben verschraubt.
6. Die Baugruppe B06_Grundaufbau_rechts montieren. Hierbei werden die zwei Bauteile T02_Tapeklemme nur leicht eingeschraubt.
7. Die Baugruppe B06_Grundaufbau_rechts wird an die Baugruppe B05_Grundaufbau_links montiert. Jetzt können auch die zwei Klemmen T02_Tapeklemme fest angezogen werden.
8. Die Baugruppe B04_Lagerung_links zusammenbauen. Dazu werden die beiden Klemmen T03_Klemme2 leicht an die Rohre T004_Verbindungsrohr geschraubt. Hier sollte der Abstand von 16,4 mm zwischen dem T019_Riemenspannerhalter und T07_Lagerung_links beachtet werden. Ebenfalls muss auf die Position der beiden Baugruppe relativ zu dem Bauteil T01_Standfuß geachtet werden, die Positionen sind in der Zeichnung B01_Wickelanlage eingezeichnet.
9. Bevor die Baugruppe B07_Antrieb_Rotation an die Rohre T004_Verbindungsrohr angebracht wird, müssen erst folgende Bauteile zusammengefügt werden. Die Riemenscheibe N_Riemenscheibe_GT2_60Z_D8 wird zusammen mit dem N_Riemen_320 auf die Welle T013_Antriebswelle aufgeschoben, der benötigte Abstand ist in der Zeichnung B07_Antrieb_Rotation angegeben. Anschließend wird die Welle T013_Antriebswelle zwischen den Bauteilen T011_Lagergehäuse und T012_Lagergehäuse eingeklemmt. Dieser Verbund wird nun an das Bauteil T09_Lagerung_rechts angeschraubt. Anschließend wird der N_Schrittmotor_Nema17 an T010_Motorbefestigung angeschraubt. Die Riemenscheibe N_Riemenscheibe_GT2_20Z_D5 wird erst auf die Schrittmotorwelle geschoben, nachdem die T010_Motorbefestigung in die Führung von der
T09_Lagerungrechts eingeführt worden ist. Die Spannung der T010_Motorbefestigung und das endgültige Anziehen der T018_Riemenklemme erfolgt später. Die Position der Baugruppe B07_Antrieb_Rotation auf den Rohren T004_Verbindungsrohr ist in Zeichnung B01_Wickelanlage angegeben.
10. Die Montage der Baugruppe B08_Verfahreinheit kann bereits vor dem Schritt 4 ausgeführt werden. Innerhalb der Baugruppe B08_Verfahreinheit wird zuerst die Baugruppe B11_Schwenktisch zusammengebaut. Zuerst müssen die N_Rillenkugellager DIN 625 6000 2Z auf die T029_Achse aufgeschoben werden, die Bemaßung ist in der Schnittansicht der Zeichnung B11_Schwenktisch angegeben. Anschließend werden die beiden Lagerhälften T030_Lager und T030_Lager_Gegenstück zusammen mit T029_Achse verschraubt. Das Bauteil T031_Hülse kann auf die T029_Achse gesetzt werden. Die Bauteile N_Riemenscheibe GT2 60Z D10 und T028_Schwenkplatte werden erst in der Baugruppe B08_Verfahreinheit montiert. Dazu wird der N_Riemen_200 auf die Riemenscheibe N_Riemenscheibe GT2 60Z D10 gelegt und mit der T028_Grundplatte verschraubt. Anschließend kann die Madenschraube der N_Riemenscheibe GT2 60Z D10 angezogen werden, nachdem diese auf die T029_Achse geschoben ist. Im Anschluss können die beiden Schrittmotoren nach der Zeichnung B08_Verfahreinheit an die Bauteile T014_Motorbefestigung2 und T032_Motorbefestigung3 angeschraubt werden. Zuletzt müssen diese an die T022_Grundplatte montiert werden.
11. Die Baugruppe B09_Materialspeicher montieren. Die Feder N_Druckfeder DIN2098 1x10x30 kann je nach Wunsch, stärker gespannt werden, indem die N_Stellring 5mm näher Richtung T037_Materialspeicher geschoben werden.
12. Der Heißluftföhn wird zwischen die Bauteile T046_HalterO und T046_HalterU geklemmt. Diese Baugruppe kann auch auf die T028_Schwenkplatte geschraubt werden. Über die Langlöcher kann die horizontale Entfernung zu dem Kern eingestellt werden. Durch Benutzung der Distanzscheiben T058_Distanzstück wird die vertikale Position zum Kern eingestellt.
13. Die Baugruppe B10_Andrückrolle nach vorliegender Zeichnung montieren. Das Bauteil T057_Tapeführung ist in mehreren Ausführungen vorhanden. Diese sind abhängig von der verwendeten Tapebreite und kann dementsprechende gewechselt werden.
14. Die Baugruppe B02_Tapeklemme auf das Bauteil T060_Kern aufschieben. Anschließend den T060_Kern an der Antriebsseite anschrauben und an der gegenüberliegenden Seite mit zwei T042_Zentrierteil fixieren.
15. Der Heißluftföhn sowie die Baugruppe B09_Materialspeicher können jetzt auf der T028_Schwenkplatte montiert werden.
16. Für die Montage der B10_Andrückrolle ist es empfehlenswert, dass Bauteil T033_Federung durch Lösen von vier Schrauben zu demontieren. Die B10_Andrückrolle auf der T028_Schwenkplatte zu montieren. Anschließend dann das Bauteil T033_Federung wieder anschrauben.
17. Der mechanische Teil der Wickelanlage ist jetzt fertig. Nun folgt der elektrische Teil.
18. Das CNC-Shield auf den Arduino UNO stecken.
19. Die Jumper auf die für die Treiber vorgesehenen Plätze gemäß der Anleitung des CNC-Shields auf 1/8 Schritte stecken.

![JumperPositionierung](https://github.com/Simon0613/Wickelmaschine/assets/149043603/27e5ed69-fb7f-4f1d-800f-202c67c8d301)


20. Die A4988 Schrittmotortreiber auf die X-, Y- und Z-Position aufstecken. Hier ist unbedingt auf die richtige Orientierung zu Achten.
21. Danach werden die Schrittmotorkabel an den Motor sowie an das CNC-Shield angeschlossen.
22. Den Arduino UNO mit Strom versorgen und das USB-B Kabel an einen Computer anschließen.
23. Estlcam auf einem Computer installieren. Anschließend können folgende Einstellungen übernommen werden.
![grafik](https://github.com/Simon0613/Winding-Machine/assets/149043603/f818d086-0682-4cda-938c-4176a4118f57)

Die Wicklung der Rohre erfolgt in folgender Reihenfolge. Grundsätzlich kann sich an die folgende Vorgehensweise gehalten werden:

![grafik](https://github.com/Simon0613/Winding-Machine/assets/149043603/25ab0d49-9c42-49ad-8679-5bfe29fae374)
Im ersten Schritt werden vorbereitende Maßnahmen durchgeführt. Dazu gehört den Kern reinigen und das Material auf den B09_Materialspeicher aufzuwickeln. Die Position der Y-Achse wird ausgerichtet, indem T022_Grundplatte und T028_Schwenkplatte parallel zueinander ausgerichtet werden. Die Z-Achse kann auf 0 gesetzt werden. Die X-Achse kann an gewünschter Position auf 0 gesetzt werden, jedoch sollte auf die ausreichende Länge geachtet werden.
Anschließend wird das Material über die T050_Umlenkrolle gelegt und durch die T039_Materialzuführ geführt. Danach wird das Material unter die Andrückrolle geführt und min. zweimal um den Kern gewickelt. Das Ende wird durch die B02_Tapeklemme festgeklemmt. Jetzt kann das Programm in Estlcam hochgela-den werden. Zuerst wird der Heißluftföhn eingeschaltet und für ca. 30 s angelas-sen. Nachdem die Vorheizzeit vorüber ist, wird das Programm gestartet. Wenn das Programm durchgelaufen ist, kann der Heißluftföhn ausgeschaltet werden und das Material wird direkt am Kern durchtrennt. Sobald der Kern abgekühlt ist, kann die-ser aus der Anlage entfernt werden. Danach kann das fertige Rohr vom Kern ab-gezogen werden.


