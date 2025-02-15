# Lesson: Digital & Serious Games

### First and Last Name: Giorgia-Ioanna Grypari
### University Registration Number: dpsd15025
### GitHub Personal Profile: https://github.com/GiorgiannaGr
### Digital & Serious Games Personal Repository: https://giorgiannagr.github.io/Role-Playing-Game/

# Introduction
Το παρόν κείμενο αποτελεί την λεπτομερή αναφορά του σχεδιασμού ενός ψηφιακού παιχνιδιού στο Unity, κατά την διάρκεια παρακολούθησης του μαθήματος "Ψηφιακά Παιχνίδια & Παιγνιώδης Μάθηση" κατά το χειμερινό εξάμηνο 2022-2023.

# Summary
Στο πρώτο παραδοτέο, δημιούργησα και διακόσμησα τον κόσμο του παιχνιδιού FunnyBunny, το οποίο έχει ως πρωταγωνιστή ένα μικρό κουνελάκι. 
Στο δεύτερο παραδοτέο, προσπάθησα να βάλω colliders χωρίς ιδιαίτερη επιτυχία λόγω των διαφορετικών επιπέδων που είχα στο background.
Στο τρίτο παραδοτέο, προσπάθησα να υλοποιήσω όσο το δυνατόν περισσότερα βήματα προκειμένου το παιχνίδι μου να φαίνεται ενδιαφέρον και δελεαστικό. Λόγω έλλειψης χρόνου, δεν κατάφερα να το φτάσω στο σημείο που ήθελα. 

# 1st Deliverable
Το συγκεκριμένο παραδοτέο αποτελεί την πρώτη μου προσπάθεια δημιουργίας ενός ψηφιακού παιχνιδιού στο Unity. 
Σε πρώτο βήμα, εγκατέστησα το Unity στον προσωπικό μου υπολογιστή, για να μπορέσω να υλοποιήσω τα ζητούμενα του πρώτου παραδοτέου.
Πριν ξεκινήσω όμως την οποιαδήποτε ενέργεια στο Unity, σχεδίασα σε ένα χαρτί το πως θα ήθελα να είναι το παιχνίδι μου 
και στη συνέχεια, όρισα τα βασικά χαρακτηριστικά τα οποία θα ήθελα να έχει:

Βασικά χαρακτηριστικά παιχνιδιού

Διαστάσεις: 2Δ,
Παίκτης/πρωταγωνιστής: μικρό κουνελάκι,
Περιβάλλον: Φυσικό περιβάλλον με σπιτάκια /σαν χωριό,
Credits/Points: Καρότα,
Enemies: Αλεπού, 
Lives: 3,
Challenge: Loading..
Βασικός πρωταγωνιστής/παίκτης είναι ένα κουνελάκι γιαυτό και το παιχνίδι ονομάστηκε FunnyBunny.

Στη συνέχεια, αφού όρισα τα βασικά χαρακτηριστικά του παιχνιδιού, ξεκίνησα να εκτελώ ένα ένα τα βήματα όπως μας υποδείχθηκαν στην εκφώνηση του παραδοτέου. 
Τα πρώτα 4 βήματα τα εκτέλεσα σχετικά εύκολα.
Όσον αφορά το 5ο & 6ο βήμα : World-Design Tilemaps & Decorating the world.
Σε αυτό το βήμα αναζήτησα στο διαδίκτυο δωρεάν tilesets τα οποία να ταιριάζουν με την αισθητική του παιχνιδιού που ήθελα να σχεδιάσω. Βρήκα κάποια τα οποία μου άρεσαν πολύ και αφού τα εγκατέστησα, ξεκίνησα να σχεδιάζω το περιβάλλον μέσα στο οποίο θα κινείται ο παίκτης μου. Στην φωτογραφία που βρίσκεται παρακάτω, φαίνεται η τελική κάτοψη του παιχνιδιού (tilemaps) και πως έχει διαμορφωθεί μέχρι στιγμής έχοντας προσθέσει τα διακοσμητικά στοιχεία:

https://github.com/GiorgiannaGr/Role-Playing-Game/blob/2aa926f03cbc609d58d627c112fd92a2d3408665/my_report/funnybunnypic.jpg 

Στην παρακάτω φωτογραφία έχω σκιαγραφήσει τις περιοχές στις οποίες θα τοποθετηθούν μελλοντικά οι εχθροί (enemies), τις περιοχες τις οποίες το παιχνίδι δεν θα αφηνει τον παίκτη να προσεγγίσει/"πατήσει", τις περιοχές στις οποίες θα εμφανίζονται τα καρότα, την αφετηρία και τέλος, έχω προσθέσει ένα EXCHANGE CENTER στο οποίο μελλοντικά ο παίκτης θα μπορεί να ανταλλάσει τα καρότα που έχει, με έξτρα ζωές. (Υπάρχει μία αμφιβολία για το αν όντως θα το πραγματοποιήσω αυτό, βλέπωντας και κάνοντας)

https://github.com/GiorgiannaGr/Role-Playing-Game/blob/2aa926f03cbc609d58d627c112fd92a2d3408665/my_report/FUNNYBUNNY2.jpg

Σε επόμενο στάδιο, πρόσθεσα τον παίκτη μου (κουνελάκι) και μέσω της εφαρμογής Visual Studio (C#) όρισα τις κινήσεις, τους άξονες στους οποίους θα κινείται (βαθμούς ελευθερίας) και την ταχύτητα με την οποία θα κινείται στο περιβάλλον του (tilemaps). Παρακάτω φαίνεται ο κώδικας: 

https://github.com/GiorgiannaGr/Role-Playing-Game/commit/4426da0a1e4cc9440c66a4df9b33141f21fa6ec2#commitcomment-90422225

Έπειτα, έκανα Build, Run, Distribute το παιχνίδι για να δω πως παίζει στο web και παρατήρησα ότι χρειάζεται κάποιες διορθώσεις. Παρ'όλα αυτά, λόγω έλλειψης χρόνου, το ανέβασα όπως είναι για να μην χάσω την προθεσμία υποβολής του παραδοτέου με σκοπό να το διορθώσω αργότερα.

Επομένως, την συγκεκριμένη χρονική στιγμή το παιχνίδι δεν βρίσκεται στην τελική του μορφή, καθώς χρειάζεται κάποιες διορθώσεις όπως:

Η κάμερα, θα πρέπει να εστιάζει ακριβώς στις διαστάσεις της κάτοψης του παιχνιδιού και όχι να "πιάνει" περισσότερο κενό χώρο γύρω από αυτό, ο οποίος φαίνεται μπλε.
https://github.com/GiorgiannaGr/Role-Playing-Game/blob/2aa926f03cbc609d58d627c112fd92a2d3408665/my_report/mple.jpg

Τα επίπεδα να διορθωθούν γιατί ο παίκτης εξαφανίζεται (πηγαίνει πίσω από το ένα επίπεδο σε κάποια σημεία).
https://github.com/GiorgiannaGr/Role-Playing-Game/blob/2aa926f03cbc609d58d627c112fd92a2d3408665/my_report/krupsimo.jpg

Τα παραπάνω προβλήματα θα διορθωθούν άμεσα για να μην αποτελούν εμπόδιο στο δεύτερο παραδοτέο.

# 2nd Deliverable

Πρωτού ξεκινήσω να εκτελώ τα βήματα του δεύτερου παραδοτέου, διόρθωσα τις αστοχίες που είχα στο πρώτο παραδοτέο τις οποίες δεν είχα κάνει την προηγούμενη φορά λόγω έλλειψης χρόνου.
Όσον αφορά τα επίπεδα, άλλαξα την τιμή στο Order in Layer προκειμένου ο παίκτης να εμφανίζεται πάνω από τα επίπεδα (Ground & Decoration). Με αυτό τον τρόπο, κατάφερα ο παίκτης μου να μην εξαφανίζεται πια κατά τη διάρκεια που περιπλανάται στον 2Δ χώρο όπως γινόταν. Έπειτα, για να διορθώσω την κάμερα έτσι ώστε να μην φαίνεται το μπλε περιθώριο γύρω από το παιχνίδι μου, σχεδίασα την περιοχή αυτή με γρασίδι. Στη συνέχεια, έκανα κάποιες αλλαγές στην διακόσμηση του παιχνιδιού, για την ακρίβεια πρόσθεσα περισσότερα διακοσμητικά στοιχεία για να φαίνεται πιο γεμάτο. Αφού έκανα όλα τα παραπάνω, προσπάθησα να προχωρήσω στην εκτέλεση των βημάτων του 2ου παραδοτέου.

1ο Βήμα: World Interactions- Blocking Movement. Σε αυτό το βήμα, παρόλο που ακουλούθησα πιστά τις οδηγίες όσον αφορά το tilemaps collider και το Composite Collider 2D, ο παίκτης μου συνεχίζει να περνά μέσα από τα εμπόδια με αποτέλεσμα να μην γίνεται κάποια συγκρουση. Στην παρακάτω φωτογραφία φαίνεται το σημείο στο οποίο βρίσκομαι και προσπαθώ να καταλάβω τι δεν λειτουργεί σωστά, ενώ έχω βάλει collider στον player. Μάλλον κάτι συμβαίνει με τα επίπεδα. Δυστυχώς μεχρι στιγμής δεν κατάφερα να καταλάβω τι φταιει.

https://github.com/GiorgiannaGr/Role-Playing-Game/blob/632d555e69124e86aaa52a51005877326f50736f/my_report/collider.jpg 

Στις παρακάτω φωτογραφίες βλέπετε σε screenshot το unity κατά την διάρκεια που μου εμφανίζονται errors τα οποία δεν μπορώ να λύσω: 

https://github.com/GiorgiannaGr/Role-Playing-Game/blob/6b8004211091fdc689b2ad67aaa38f4c70580266/my_report/error.jpg

https://github.com/GiorgiannaGr/Role-Playing-Game/blob/969a356d7e6f34192f67b8acda74a3462727b292/my_report/error2.jpg

Σε αυτό το σημείο, αποφάσισα ότι δεν μπορει να προχωρήσει παρακάτω το 2ο παραδοτέο γιαυτο και σταμάτησα την όποια προσπάθεια για να το ολοκληρώσω. 

# 3rd Deliverable 
Όσον αφορά το 3ο παραδοτέο:

Σε πρώτη φάση, προσπάθησα να υλοποιήσω τα βήματα του 2ου παραδοτέου για να συνεχίσω με την υλοποίηση των υπολοίπων βημάτων. Δυστυχώς δεν καταφερα να βρω λύση όσων αφορά τα tilemaps colliders και το composite collider 2D και αυτό διότι εχω δυο διαφορετικά επίπεδα που αποτελουν το background. Επομένως, μαλλον γιαυτό οταν βαζω colliders στα εμποδια ο παικτης δεν μπορεί να λειτουργήσει σωστά και περνάει από πάνω τους. 

Το παιχνίδι χωρίς να λειτουργούν οι colliders δεν φαίνεται ρεαλιστικό, κι αφου το προσπαθησα και δεν βρηκα λύση, αποφάσισα να παραβλέψω αυτό το βήμα.

Αμέσως μετά, προχώρησα στην προσθήκη των coins που θα μαζεύει ο παίκτης μου (τριφύλλια και οχι καρότα τελικά). Έβαλα και στα coins colliders γνωρίζοντας ότι αντιμετωπίζω πρόβλημα και δεν θα λειτουργήσουν. Σε αυτό το σημείο να τονίσω ότι στόχος του παιχνιδιού είναι να μαζέυει ο παίκτης μου όσα περισσότερα τριφύλλια γίνεται για να κερδίζει πόντους. Τα τριφύλλια σε ιδανικό σενάριο θα μπορεί να τα μαζεύει και αυτά να ξανα εμφανίζονται ύστερα από ένα συγκεκριμένο χρονικό διάστημα.
Στη συνέχεια, πρόσθεσα τις επικύνδινες ζώνες του παιχνιδιού δηλ. τοποθέτησα σε διάφορα σημεία βόμβες μικρές και σε κάποια άλλα σημεία, βόμβες μεγαλύτερες. Επίσης, πρόσθεσα σε κάποια σημεία αντίδοτα (ειδικά φίλτρα που βελτιώνουν την ζωή του παίκτη και φάρμακα που του δίνουν έξτρα ζωή). Πάλι όμως αντιμετωπίζοντας το ίδιο πρόβλημα με τους colliders. 

Σε συγκεκριμένο σημείο του παιχνιδιού έχω προσθέσει έναν πάπυρο. Με το που συλλέγει τον πάπυρο θα του εμφανίζεται ένα μήνυμα το οποίο θα λέει ότι πρέπει να μαζέψει τα 5 χάλκινα νομίσματα τα οποία βρίσκονται σε τυχαίες θέσεις στο παιχνίδι προκειμένου να μπορέσει να αγοράσει ένα από τα σπαθιά τα οποία θα τον βοηθήσουν να πολεμήσει τον εχθρό (το ρομπότ). Το ρομπότ θα χάνει το 1/3 της ζωής του κάθε φορά που ο παίκτης το χτυπάει με το ένα σπαθί. Για να αποτελειώσει ο παίκτης το ρομπότ, θα πρέπει να το χτυπήσει 3 φορές, όσα είναι και τα σπαθιά στο παιχνίδι συν να έχει στην κατοχή του το σχοινί. Αν ο παίκτης καταφέρει να νικήσει το ρομπότ αυτό θα εξαφανίζεται και θα επανεμφανίζεται μετά από συγκεκριμένο χρονικό διάστημα 10 δευτερολέπτων. 
Αν και δεν υλοποιούνται στην πραγματικότητα, λόγω των colliders, οφείλω να αναφέρω ποιος ήταν ο σκοπός μου κατά την σχεδίαση του.

Τέλος, πρόσθεσα μουσική στο παιχνίδι για να είναι πιο ενδιαφέρον και πιο ελκυστικό για τον παίκτη.

Στην παρακάτω φωτογραφία βλέπουμε την τελική εικόνα του παιχνιδιού όπως έχει διαμορφωθεί.

https://github.com/GiorgiannaGr/Role-Playing-Game/blob/7136f04a07f42ad3835e2c5c992e341f81345a57/my_report/Screenshot%202023-01-12%20134915.jpg 


# Conclusions
Συμπερασματικά, το Unity είναι ένα πολύ εύχρηστο και καλό εργαλείο για να δημιουργήσει κανείς το πρώτο του ψηφιακό παιχνίδι. Αν είχα στην διάθεσή μου περισσότερο χρόνο, θα ήθελα να είχα ολοκληρώσει ένα άριστα λειτουργικό και ψυχαγωγικό παιχνίδι για τους μικρούς μας φίλους, το FunnyBunny. Δεν τα κατάφερα διότι έκανα όλο αυτό το διάστημα παράλληλα την διπλωματική μου. Παρόλα αυτά, θεωρώ πως έχω αποκτήσει κάποιες βασικές γνώσεις και πως μελλοντικά ίσως να το υλοποιήσω. 

# Sources
