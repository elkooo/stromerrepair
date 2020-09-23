# stromerrepair
Reverse engeneeren des ersten Stromers um Motorschäden via DIY-lösung zu beheben<br>
<br>
<b>Absicht:</b><br>
<br>
Entwickeln einer Lösung zur Behebung der «Motorschäden» bei Stromer ST1 Pedelecs.<br>
Diese Motorschäden sind meist Probleme des Controllers (Überhitzung und dadurch Schäden an der im Motorgehäuse verbauten Elektronik oder den Sensoren). <br>
Entwickelt werden soll eine Steuerung und Software, welche den bestehenden Controller ersetzt und so das Rad erneut auf die Strasse bringt.<br>
<br>
<b>Konzept:</b><br>
<br>
Als IC soll ein Arduino (oder Atmel-Chip) zum Einsatz kommen. Dieser soll:<br>
•Mit dem Originaldisplay kommunizieren<br>
•Den bestehenden Drehmomentsensor auslesen<br>
•Die Akkuspannung messen und überwachen<br>
•Einen Brushless ESC ansteuern<br>
<br>
Der ESC (Electronic Speed Controller) muss vermutlich etwas überdimensioniert werden, damit er nicht in Rauch aufgeht - sinnvoll wäre wohl etwas um die 1500w, auch wenn keine so hohen Energiespitzen erreicht werden.<br>
Da die Akkus keine Kommunikationsschnittstelle haben, geht das mit den Orig. Akkus relativ einfach.<br>
Dort liegen normalerweise einfach die 36v (bzw. irgendwas zw. 33v und 42v je nach Ladezustand) an den Polepins an. <br>
Der Originale ESC soll aus dem Motorgehäuse ausgebaut werden, die Kabel von den Wicklungen sowie anschlüsse der Hall-Sensoren neu verkabelt und durch die Nabe rausgezogen werden. Der Controller sollte so klein gebaut sein, dass er im Rahmen unterbringbar ist. So wird auch dem Überhitzungsproblem der Elektronik im Motorengehäuse entgegnet. <br>
<br>
Diskussionsforum: https://stromerforum.ch/showthread.php?tid=2967
