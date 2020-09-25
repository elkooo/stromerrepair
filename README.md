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
Diskussionsforum: https://stromerforum.ch/showthread.php?tid=2967<br>
<br>
<b>Mögliche Hardware:</b><br>
<br>
Mögliche Controller:<br>
https://vesc-project.com (Programmierbare VESC Controller! Sehr cool!)<br>
https://makerx-tech.com/collections/x-esc/products/x-vesc4<br>
https://www.aliexpress.com/item/4000438827676.html?spm=a2g0o.productlist.0.0.3d007eb1LHN08B&algo_pvid=cb375965-7afa-4e7d-8565-c93923862e3f&algo_expid=cb375965-7afa-4e7d-8565-c93923862e3f-2&btsid=0bb0623916010394170761445e2f7f&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_a
