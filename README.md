# PC Bauprojekt Simon Alex Johannes

## Unsere Komponenten
Hier Vergleichliste von Geizhals eingeben:

## Schritt 1 Mainboard
Mainboard auspacken und auf Schäden kontrollieren. Am besten auf denn Karton legen. ==Nicht auf die Folie legen in der das Mainboard eingepackt ist wie in so machen Anleitungen zu sehen. Hierbei kann das Mainboard durch Statische aufladungen beschädigt werden da die Folie Außen Leitfähig ist und so Spannungen weitergeleitet werden können.
![[WhatsApp Image 2022-12-01 at 09.37.43.jpeg]]

## Schritt 2 Prozessormontage
Vor dem Einlegen ob Pins von der CPU verbugen sind. Sollte dieser der Fall sein vor dem Einlegen ausbiegen so kann an größerer Schaden verhindert werden.
In der Anleitung des Mainboards nachlesen wie die CPU montiert werden muss. Hier muss der Hebel am Sockel umgelegt werden. ==Die CPU muss so eingelegt werden das das Goldene Dreieck auf dem Dreicke im Sockel passt.== 
![[WhatsApp Image 2022-12-01 at 09.37.39.jpeg]]

## Schritt 3 Wärmeleitpaste
Die Kontakt Fläche mit Spiritus oder besser mit Isopropanol reinigen. Die Metallischen Anschraubpunkwinkel auf der Platzhalterung einschnappen. 
Eine Erbsengroße Menge mittig auf der CPU plazieren. ![[WhatsApp Image 2022-12-01 at 09.37.37.jpeg]]
==Nicht mehr das diese sonst an den Seiten herunter und in den Sockel laufen kann wie in diesem Bild ersichtlich==
![[WhatsApp Image 2022-12-01 at 09.37.39 (1).jpeg]]
## Schritt 4 CPU Kühler
CPU Kühler zentriert auf der CPU Aufsetzten und anschrauben. ==Nicht mehr anheben da sonst Luftblasen in der Wärmeleitpastenschicht enstehen können die die Wärme übertragung verringern== Außerdem ist darauf zu Achten den CPU Kühler so wenig wie möglich seitwerts zu verschieben.
==Nicht zu fest anziehen da sonst das Mainbord verbogen werden kann (ca. 3Nm)==

![[WhatsApp Image 2022-12-01 at 09.37.07 (1).jpeg]]
Jetzt den Lüfter des CPU Kühler mit dem am Mainboard vorgesehen Anschluss CPU_FAN verbinden. Hierbei auf die Richtige Orentierung Achten. Die Nase des Mainboardsteckers muss in die Einkerbung an der Lüfterbuchse. ![[WhatsApp Image 2022-12-01 at 09.37.07.jpeg]]

## Schritt 4 Arbeitsspeicher
Arbeitspeicherriegel in die laut Mainboardhandbuch vorgesehenen Plätze für Dualchannel einsetzen. ==Korrekte Orentierung über die Einkerbung auf der Kontaktleiste sicherstellen==
![[Pasted image 20221201230124.png]]


## Schritt 5 Mainboard in Gehäuse einlegen
==Davor den Stecker für die Stromversorgung der CPU mit dem Mainboard verbinden da diese Buchse im Eingebauten zustand sehr schwehr ereichbar ist.== 
![[Pasted image 20221201223033.png]]

![[Pasted image 20221201221543.png]]
Dann Mainboard an den ==9 Anschraubpunkten== mit den beim Gehäuse beiligenden M3 schrauben befestigen. ==Nicht zu fest anziehen da es sonst Riße im Mainboard geben kann (ca. 1Nm)==
![[WhatsApp Image 2022-12-01 at 09.37.06 (1).jpeg]]

## Schritt 6 Netzteil einbauen
Netzteil an den 4 Anschraubpunkten mit den M3 Schrauben die auch schon fürs Mainboard genutzt werden befestigen.
![[WhatsApp Image 2022-12-01 at 09.37.05.jpeg]]

## Schritt 7 Speicher (2.5" SSD) einbauen
An den 4 Anschraubpunkten mit den M2 Schrauben befestigen.
![[WhatsApp Image 2022-12-01 at 09.37.04 (1).jpeg]]
## Schritt 8 Leitungen anschließen
### IO Blende
![[Pasted image 20221201223236.png]]
==Hierbei ist bei Powerled und HDDLED auf die korekte Polarität zu achten da es DIODEN sind.==
Bei Reset SW und Powersw ist die ausrichtung egal. Bei unklarheiten in der Mainboardanleitung nachlesen
![[Pasted image 20221201223720.png]]
### Frontpanel Audio
![[Pasted image 20221201223842.png]]
Darauf achten das die Fehlende Pin Buchse auf den Fehlen Pin am Mainboardstecker gesetzt wird.
![[Pasted image 20221201224136.png]]
### USB 3
![[Pasted image 20221201224323.png]]
USB 3 Buchse (meißt Blau) in diesen Stecker am Mainboard anschließen
![[Pasted image 20221201224515.png]]
### USB 2
![[Pasted image 20221201224553.png]]
Der Stecker ist erkennbar an seinem Verschloßenen außern Kontakt
![[Pasted image 20221201224718.png]]
Hier sind die Stecker am Mainboard klar gekennzeichnet
![[Pasted image 20221201224824.png]]
### SATA Strom und Datenverbindung
![[Pasted image 20221201224910.png]]
![[Pasted image 20221201225117.png]]
Diese Buchsen an der SSD anstecken. Auf die Ortierung achten.
![[Pasted image 20221201225141.png]]
Das andere Ende der Datenverbindungleitung am Mainboard anschließen.
Hier von oben links nach rechts anschließen das die Datenträgen die Richtige Nummer bekommen.

![[Pasted image 20221201225232.png]]
### Mainboard
![[WhatsApp Image 2022-12-01 at 09.36.56.jpeg]]
Auf gerade Ausrichtung achten da sonst mehr Kraft benötigt wird den Stecker anzuschließen und dadurch das Mainbord unnötigen Belastungen ausgesetzt wird.
![[Pasted image 20221201225544.png]]
### GPU
![[Pasted image 20221201225637.png]]
Diese Buchse für die GPU wird bei unserm System nicht benötigt da die CPU durch den Rückwandbus des Mainboard versorgt wird.


## Betriebsysteminstallation
### USB Starten aus UEFI
Ins Bios booten und im Bootmenu USB Stick mit System Iso Datei auswählen ==Gerätename mit UEFI das richtige installation ausgeführt wird==
![[IMG_20221121_103103.jpg]]
In Ventoy Iso auswählen
![[IMG_20221121_103204.jpg]]
Sprache auf Deutsch stellen
![[IMG_20221121_103437.jpg]]

Installationsziel auswählen
![[IMG_20221121_103559.jpg]]
Und installation Starten
![[IMG_20221121_103700.jpg]]
Ist die Installion erfolgreich kann die der PC ausgeschaltet werden und an den Kunden übergeben werden
![[Pasted image 20221201231133.png]]
