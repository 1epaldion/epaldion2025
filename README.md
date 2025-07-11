<font color="blue"><center><h2>1ο ΕΠΑΛ Διονύσου-"Ζήνων"</h2><center></font>

<h2>&#9997;Βασική ιδέα</h2>

Οι δημόσιες τουαλέτες λόγω της μεγάλης επισκεψιμότητάς τους πρέπει να χρησιμοποιούνται σωστά ώστε να μην παρατηρούνται προβλήματα καθαριότητας και να υπάρχει αίσθημα ασφάλειας. Ειδικά στις σχολικές τουαλέτες είναι αναγκαία η προσοχή στη σωστή χρήση τους. 
Φαινόμενα όπως η μη ρίψη νερού μετά τη χρήση, η ρίψη απορριμμάτων εντός της λεκάνης, κάπνισμα μέσα στις τουαλέτες, μη σεβασμός των τουαλετών ΑΜΕΑ από μη δικαιούχους, μη τήρηση προσωπικής υγιεινής, δείχνουν έλλειψη ενημέρωσης, έλλειψη παιδείας και αδιαφορία για ένα δημόσιο χώρο.
Αυτή λοιπόν η μελέτη στοχεύει στη σωστή λειτουργία των δημόσιων και ειδικά σχολικών τουαλετών, όσον αφορά την καθαριότητα και την υγιεινή, καθώς και την ασφάλεια των πολιτών, κάτι που αποτελεί βασικό στοιχείο σεβασμού αλλά και δημόσιας υγείας. <br>
Οι εκπαιδευτικοί στόχοι του έργου είναι οι μαθητές να μπορούν:<ul>
<li>Να προτείνουν λύσεις για κάποιο πρόβλημα που παρουσιάζεται
<li>Να οργανώσουν τα βήματα που θα ακολουθήσουν
<li>Να σχεδιάσουν και να υλοποιήσουν
<li>Να αναπτύξουν υπολογιστική σκέψη και να προγραμματίσουν
<li>Να δουλέψουν ομαδικά
<li>Να ευαισθητοποιηθούν για τη σωστή χρήση των δημόσιων χώρων
<li>Να προωθήσουν τη δουλειά τους προς όφελος της κοινότητας</ul>

<h2>&#128195;Περιγραφή έργου</h2>

Η ομάδα μας στα πλαίσια του 7ου Πανελλήνιου Διαγωνισμού Ανοιχτών Τεχνολογιών στην Εκπαίδευση υλοποίησε ένα έργο με τίτλο <b>«Ασφάλεια και την τήρηση κανόνων σε δημόσια τουαλέτα».</b>
Οι μαθητές της σχολικής ομάδας ρομποτικής δημιούργησαν μία κατασκευή που αναπαριστά μία δημόσια τουαλέτα. Στην κατασκευή ενσωματώθηκαν αυτοματισμοί που ενεργοποιούνται ανάλογα με τις συνθήκες που επικρατούν στον συγκεκριμένο χώρο. Χρησιμοποιήθηκαν μικροελεγκτές Arduino Uno και οι απαραίτητοι αισθητήρες. <br>
Το έργο μας υλοποιείται με δύο διατάξεις:<br>
<ul><li>	Στην πρώτη διάταξη χρησιμοποιείται <b>arduino Uno</b>,  αισθητήρας <b>MQ2</b>, οθόνη <b>LCD (20x4 I2C)</b>, βομβητής-<b>buzzer</b> και <b>LED.</b> Σκοπός είναι η παρακολούθηση της ποιότητας του αέρα μέσω του αντίστοιχου αισθητήρα ενώ εμφανίζει δεδομένα στην οθόνη και ενεργοποιεί το βομβητή και το led, σε περίπτωση ανίχνευσης καπνού ή αερίου σε υψηλά επίπεδα.

<li>Στη δεύτερη διάταξη χρησιμοποιείται <b>arduino Uno</b>,  αισθητήρας <b>PIR</b> (κίνησης), αισθητήρας ήχου <b>KY-038</b>, <b>ηχείο</b> και <b>DFPlayer Mini</b>. Σκοπός είναι μόλις εντοπίζει κίνηση να παίζει ένα αρχείο ήχου με ηχογραφημένο μήνυμα για σωστή χρήση της τουαλέτας και αν ακουστεί κάποιος δυνατός ήχος ή κάποιος φωνάξει για βοήθεια να παίξει ένα αρχείο ήχου όπου ακούγεται ήχος σειρήνας. </li></ul>

<h2>&#128209;Λειτουργία προγράμματος</h2>
Στη <b>πρώτη</b> διάταξη το πρόγραμμα παρακολουθεί την έξοδο του αισθητήρα MQ2. Όσο τα επίπεδα καπνού ή αερίων είναι σε χαμηλά επίπεδα, στην οθόνη εμφανίζεται μήνυμα με την τιμή του αισθητήρα, την τάση που "βλέπει" ο αισθητήρας MQ2 στην έξοδο του και την κατάσταση του αέρα, η οποία κατατάσσεται σε "Καθαρή" (Clean) ή "Μέτρια" (Moderate) ανάλογα με την τιμή. <br>Αν τα επίπεδα καπνού ή αερίων περάσουν την τιμή 600, τότε ενεργοποιείται το buzzer προειδοποιώντας για τα υψηλά επίπεδα, ανάβει το led και στην οθόνη εμφανίζεται το μήνυμα <b>"HIGH SMOKE INTENSITY BE AWARE"</b>.<p><br>
Στη <b>δεύτερη</b> διάταξη όταν ο αισθητήρας κίνησης PIR ανιχνεύσει κίνηση, ενεργοποιείται το αρχείο 0001.mp3, που είναι αποθηκευμένο στη κάρτα SD. Μεταξύ δύο εντοπισμών κίνησης υπάρχει καθυστέρηση 18 sec, μέχρι την ενεργοποίηση πάλι του μηνύματος, και αυτό συμβαίνει ώστε να μην υπάρχει αλληλοκάλυψη.<br>
Το αρχείο 0002.mp3 που περιέχει ήχο σειρήνας, ενεργοποιείται όταν ο αισθητήρας ήχου KY-037 ανιχνεύσει δυνατή φωνή ή χτύπο. Μεταξύ δύο ήχων υπάρχει καθυστέρηση 5sec. Οι ήχοι παίζονται μέσω του DFPlayer Mini, που διαβάζει τα αρχεία από την κάρτα SD.

<h2>&#128736;Κατασκευή Μακέτας</h2>
Η βάση της μακέτας είναι ένα μακετόχαρτο 50x70. Τα τοιχώματα είναι από μακετόχαρτο και κόπηκαν βάση του σχεδίου κάτοψης που φτιάχτηκε με online λογισμικό. Δημιουργήθηκαν τρεις τουαλέτες, μία γυναικών, μία ανδρών και μία για ΑΜΕΑ. Τα είδη υγιεινής που περιέχει η μακέτα είναι νιπτήρας με κολόνα, καθρέφτης και λεκάνη. Η λεκάνη αποτελεί έτοιμο σχέδιο ενώ τα υπόλοιπα σχεδιάστηκαν στο tinkercad. Εκτυπώθηκαν σε 3D εκτυπωτή και χρειάστηκαν σύνολο 27 ώρες. Στο πάτωμα των τουαλετών κολλήθηκε χαρτόνι με σχέδια. Στις ενώσεις των τοιχωμάτων τοποθετήθηκαν κομμάτια ξύλου balsa και στα σημεία της οροφής κομμάτια από τη ράβδο balsa. Εξωτερικά βάφτηκαν τα τοιχώματα και κολλήθηκε χαρτόνι διαφορετικού σχεδίου.<br>

<h2>&#128176;Υλικά</h2>
Τα υλικά που τελικά χρησιμοποιήθηκαν για την υλοποίηση των αυτοματισμών είναι τα παρακάτω:<br><br>
<table>
<tr><td><b>Α/Α</b></td><td><b>Περιγραφή</b></td><td><b>Τιμή</b></td></tr>
<tr><td>1</td><td>Arduino Uno x 2</td><td>59.80€</td></tr>
<tr><td>2</td><td>Breadboard</td><td>2.20€</td></tr>
<tr><td>3</td><td>HC-SR501</td><td>2.80€</td></tr>
<tr><td>4</td><td>KY-038</td><td>1.20€</td></tr>
<tr><td>5</td><td>MQ2</td><td>8.60€</td></tr>
<tr><td>6</td><td>LCD 20x4</td><td>9.90€</td></tr>
<tr><td>7</td><td>Buzzer 5V-Passive</td><td>0.60€</td></tr>
<tr><td>8</td><td>DFPlayer-A Mini MP3 Player</td><td>9.90€</td></tr>
<tr><td>9</td><td>Breadboard Jumper Wires</td><td>3.60€</td></tr>
<tr><td>10</td><td>LED Red Diffused 5mm & Resistor 200Ω</td><td>0.80€</td></tr>
<tr><td>11</td><td>Speaker Enclosed 2W 8Ohm-20x30mm</td><td>2.40€</td></tr>
<tr><td>12</td><td>Sandisk Ultra microSDHC 32GB</td><td>7.00€</td></tr>
<tr><td></td><td><b>Σύνολο</b></td><td>108.80€</td></tr> 
</table>
Τα υλικά για την κατασκευή της μακέτας είναι τα παρακάτω:<br><br>
<table>
<tr><td><b>Α/Α</b></td><td><b>Περιγραφή</b></td><td><b>Τιμή</b></td></tr>
<tr><td>1</td><td>Μακετόχαρτο 50x70 5mm x 3</td><td>15.00€</td></tr>
<tr><td>2</td><td>Ράβδος Τετράγωνη Balsa 10mm x2</td><td>2.00€</td></tr>
<tr><td>3</td><td>Φύλλο Balsa 5mm x2</td><td>4.00€</td></tr>
<tr><td>4</td><td>Χαρτόνι με σχέδιο x2</td><td>1.40€</td></tr>
<tr><td>5</td><td>Νήμα PLA</td><td>13.00€</td></tr>
<tr><td>6</td><td>Χρώματα-κόλλα-σιλικόνη</td><td>5.00€</td></tr>
<tr><td></td><td><b>Σύνολο</b></td><td>40.40€</td></tr> 
</table>
<h3><b>Συνολικό κόστος κατασκευής έργου 149,20€</b></h3>

<h2>&#128190;Λογισμικό</h2>
Χρησιμοποιήθηκε λογισμικό ανοιχτού κώδικα και online δωρεάν λογισμικό.<br><ul>
<li>Η συγγραφή του κώδικα έγινε στο περιβάλλον Arduino IDE.
<li>Το ηχητικό μήνυμα προέρχεται από την ιστοσελίδα elevenlabs.io -Free Text to Speech & AI Voice Generator.
<li>Το σχέδιο της λεκάνης προέρχεται από την ιστοσελίδα https://www.thingiverse.com.
<li>Τα σχέδια των υπολοίπων ειδώ υγιεινής δημιουργήθηκαν στο tinkercad.
<li>Τα σχέδια 3D κάτοψης δημιουργήθηκαν με το https://www.coohom.com
<li>Η μετατροπή των αρχείων σε τύπο gcode έγινε με το λογισμικό Cura.
<li>Η βιντεοσκόπηση και η επεξεργασία έγινε με το λογισμικό Capcut με χρήση κινητού τηλεφώνου
<li>Τα σχεδιαγράμματα ηλεκτρονικό και ηλεκτρολογικό έγιναν με το λογισμικό fritzing έκδοση BETA</ul>

<h2>&#127886;Η ομάδα μας</h2>
Η <b>ομάδα</b> μας αποτελείται από τους:
<ol><li>Παπαδόπουλο Θεόδωρο
<li>Βλάχο Χρήστο
<li>Αντάλιαλη Σωτήριο
<li>Κοντάκη Νικόλαο
</ol>
<b>Υπεύθυνες Καθηγήτριες:</b>
<ul><li>Χατζηανδρέου Ελένη ΠΕ86
<li>Κωστοπούλου Ιωάννα ΠΕ83</ul>









