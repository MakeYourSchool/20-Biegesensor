Biegesensor
----
*(Flex Sensor 2.2")*

<img src=https://www.makeyourschool.de/wp-content/uploads/2018/10/20_biegesensor-1024x1024.jpg width=400px>

Der Biegesensor ermöglicht es, Verbiegungen zu erkennen und deren Ausmaß zu bestimmen. Wird der Fühler des Sensors gebogen (Aufrollbewegung mit den Metallplättchen nach außen), ändert sich der elektrische Widerstand zwischen den Anschlusspins. Durch eine Widerstandsmessung kann folglich auf die Biegung des Fühlers geschlossen werden.

Da ein Arduino nicht direkt eine Widerstandsänderung messen kann, wird hier eine Messverstärkerschaltung benötigt. Eine Möglichkeit bietet hierfür ein sogenannter Spannungsteiler, bei dem der Sensor in Reihe mit einem zweiten Widerstand zwischen Versorgungsspannung und Masse gelegt wird. Der Arduino kann schließlich die Widerstandsänderung als Spannungsänderung über einen analogen Pin erfassen.

Eine häufige Anwendung des Biegesensors ist die Nutzung in einem Sensorhandschuh. Hier kann unter anderem die Beugung der Finger erfasst werden.

Man findet über alle gängigen Suchmaschinen meist nur mit der Eingabe der genauen Komponentenbezeichnung entsprechende Projektbeispiele und Tutorials. Hierbei ist das wichtige Stichwort „FSR“ (force sensing resistor).

----

In diesem Repository findet ihr **Bibliotheken und Beispiel-Codes**, mit denen der hier vorliegende Sensor getestet werden kann. Wir richten uns hiermit an **jeden Mentor und jede Mentorin aus dem Rahmen von Make Your School** und ermutigen euch, die hier zusammengestellten Codes **nach Bedarf** und individuell gemachten Erfahrungen **anzupassen**. Beispiele können einfach im Ordner /examples hinzugefügt oder angepasst werden. Wir versuchen das Repository regelmäßig mit Hilfe von euren Änderungsvorschlägen zu aktualisieren.


**Weitere Informationen:**

[Materialkoffer von Make Your School](https://www.makeyourschool.de/material/)
