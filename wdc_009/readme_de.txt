Die ist die readme Datei zu unserem WDC_009 Theme.

Erst mal vielen Dank das Du Dich f�r unser WDC_009 entschieden hast.

Diese Readme Datei soll Dir helfen die Navigation und die Reflektion f�r Bilder anzupassen.

Die html Datei f�r das Men� findest Du in folgendem Ordner: menu. Die zu bearbeitende html Datei hei�t: menu.html

Jeder Link ist wie folgt aufgebaut:

<a class="dock-item" href="index.php"><img src="<{xoImgUrl menu/images/025.png}>" alt="Home" /><span>Home</span></a>

Bitte bearbeite nur folgende Optionen, sonst arbeitet das Menu nicht mehr:

1. href="" gebe hier die Url ein die Du verlinken m�chtest, Beispiele wie das geht siehst Du in der Datei
2. den image tag: hier brauchst Du nur die Nummer des Bildes �ndern. In dem Pack sind 131 Bilder dabei, welche schon fertig f�r das Men� sind
3. alt="" Trage hier den Namen des Moduls ein welches Du verlinken m�chtest, Beispiele findest Du in der Datei
4. Den Namen des Modules gibst Du zwischen den <span></span> tags ein. Das zeigt den Namen des Men�s unter dem Bild.

Wenn Du deinen Bildern eine Reflektion geben m�chtest, wie bei den Bl�ttern neben dem Blocknamen, dann musst Du bei den Bildern im img tag nur folgende Klasse hinzuf�gen: class="reflect". Das passiert dann in den Templates des Modules! Das w�rde dann so aussehen <img src="" class="reflect" />


Viel Spa�
Euer WDC Team
