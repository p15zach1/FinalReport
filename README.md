# Τελική Αναφορά
## Ζαχαριάδης Αλέξανδρος
### ΑΜ: Π2015082
#### e-mail: p15zach1@ionio.gr  
#### [Αποθετήριο Μαθήματος Τεχνολογίες Λογισμικού](https://github.com/p15zach1/sw)  
#### [Αποθετήριο Data Visualizer](https://github.com/p15zach1/D3js-uk-political-donations)  
#### [Ιστοσελίδα Data Visualizer](https://p15zach1.github.io/D3js-uk-political-donations)

## Σύνοψη:  
Έγινε εξοικείωση με τη βιβλιοθήκη D3 της JavaScript, η οποία χρησιμοποιείται για την οπτικοποίηση δεδομένων. Χρησιμοποιώντας τη λειτουργία github pages του Github, δημιουργήθηκε ιστοσελίδα που οπτικοποιεί δεδομένα με διάφορες δυνατότητες που στοχεύουν στις ανάγκες χρηστών με προβλήματα όρασης.  

## Εισαγώγη:  

## Επιλογή Εργαλείων:  

## Διαδικασία και Μέθοδος Ανάπτυξης: 
### Παραδοτέο 1  
Μετά το fork του αποθετηρίου, έγινε μετονομασία του αρχείου full-viz.html σε index.html έτσι ώστε, να μη χρειάζεται το link της ιστοσελίδας που προβάλλει τα δεδομένα να καταλήγει σε ".html". Στη συνέχεια, άλλαξα τα χρώματα στις μπάλες δεδομένων, καθώς και στα πεδία της ενότητας "split by party" για να είναι ίδια με τα καινούρια χρώματα. Ύστερα, προστέθηκε ένα αρχείο ήχου στο αποθετήριο και γράφτηκε κατάλληλος κώδικας, για να ακούγεται ο προειπώμενος ήχος κάθε φορά που ο χρήστης πατάει οποιαδήποτε επιλογή ομαδοποίησης δεδομένων. Το επόμενο ζητούμενο του παραδοτέου αφορούσε τη διευκόλυνση των χρηστών για την αναζήτηση πληροφοριών για τους δωρητές. Αυτό επιτεύχθηκε με την προσθήκη κατάλληλου κώδικα έτσι ώστε, κάθε φορά που κάνεις κλικ σε κάποια μπάλα δεδομένων να ανοίγει σε νέο παράθυρο του browser μια αναζήτηση στο Google για το δωρητή που επιλέχτηκε. Επίσης, χρειάστηκε ένας τρόπος για να γίνεται zoom σε κάποιο κείμενο όταν το βελάκι πηγαίνει από πάνω του. Για αυτόν το λόγο, προστέθηκε στο τέλος του κώδικα ένα καινόυριο zoom function και γράφτηκε όπου χρειαζόταν το "class=zoom", έτσι ώστε να καλείται το καινούριο function για εκείνο το κείμενο που δείχνει το ποντίκι. Με μία λειτουργία speech synthesis, κάθε φορά που το βελάκι παέι πάνω από κάποια μπάλα δεδομένων, ακούγεται το όνομα του δωρητή του και το ποσό που δώρησε. Αν το ποντίκι βγει από τη μπάλα πριν τελειώσει η ομιλία, τότε η ομιλία θα σταματήσει. Επιπλέον, έγινε προσθήκη νέας επιλογής ομαδοποίησης δεδομένων και πιο συγκεκριμένα, ομαδοποίηση με βάση το ποσό που δωρήστηκε από τον κάθε δωρητή ξεχωριστά. Για αυτόν το σκοπό χρειάστηκε η προσθήκη νέου κώδικα σε κάθε αρχείο. Στο "chart.js" προστέθηκαν καινούρια functions για τη λειτουργία της νέας επιλογής, καθώς και εντολές fadeOut και fadeIn για να εμφανίζεται ή να κρύβεται η νέα ομαδοποίηση ανάλογα. Στο "index.html" γράφτηκαν στο τέλος του κώδικα τα κείμενα που θα βγαίνουν στη νέα επιλογή. Τελευταία, στο "style.css" προστέθηκαν οι τοποθεσίες που θα βγαίνουν τα νέα κείμενα και κρύφτηκαν κατά τη σύνδεση στη σελίδακ, για να φαίνεται μόνο η πρώτη επιλογή ομαδοποίησης.  

* Προσθήκη συνδέσμου της σελίδας
* Αλλαγή έτσι ώστε το url να μην καταλήγει σε "full-viz.html" μετονομάζοντας το full-viz.html σε index.html
* Αλλαγή χρωμάτων στις μπάλες δεδομένων και στα πεδία ομαδοποίησης Split by party  
[chart.js](https://github.com/p15zach1/D3js-uk-political-donations/blob/gh-pages/chart.js)  
[style.css](https://github.com/p15zach1/D3js-uk-political-donations/blob/gh-pages/style.css)  

* Ακούγεται ήχος κάθε φορά που κάνεις κλικ σε κάποια επιλογή ομαδοποίησης  
[index.html](https://github.com/p15zach1/D3js-uk-political-donations/blob/gh-pages/index.html)

* Όταν κάνεις κλικ σε κάποια μπάλα δεδομένων τότε ανοίγει νέο παράθυρο με αναζήτηση για τον αντίστοιχο δωρητή στη μηχανή αναζήτησης Google  
[chart.js](https://github.com/p15zach1/D3js-uk-political-donations/blob/gh-pages/chart.js)

* Το ποντίκι λειτουργεί σαν μεγεθυντικός φακός όταν είναι πάνω από κάποιο κείμενο  
[index.html](https://github.com/p15zach1/D3js-uk-political-donations/blob/gh-pages/index.html)  

* Όταν το ποντίκι είναι πάνω σε κάποια μπάλα δεδομένων τότε ακούγεται η ονομασία του δωρητή και του ποσού που δώρησε  
[chart.js](https://github.com/p15zach1/D3js-uk-political-donations/blob/gh-pages/chart.js)

* Δημιουργήθηκε μία καινούρια επιλογή ομαδοποίησης δεδομένων Split by amount  
[chart.js](https://github.com/p15zach1/D3js-uk-political-donations/blob/gh-pages/chart.js)  
[index.html](https://github.com/p15zach1/D3js-uk-political-donations/blob/gh-pages/index.html)  
[style.css](https://github.com/p15zach1/D3js-uk-political-donations/blob/gh-pages/style.css)  

* Δημιουργήθηκε ένα ".csv" αρχείο, στο φάκελο participants του αποθετηρίου, με τα στοιχεία μου
* Προστέθηκαν 5 είκονες, στο φάκελο photos του αποθετηρίου, για τα φυσικά πρόσωπα ή τα λογότυπα των παρακάτω δωρητών
  1. FBU (14)
  2. Zac Goldsmith (96)
  3. Michael Farmer (98)
  4. Andrew Law (106)
  5. Michael Hintze (116)  
  
### Παραδοτέο 2  
Προστέθηκε κώδικας στο αρχείο "chart.js" για την δυναμική εμφάνιση των εικόνων των δορητών πάνω από τους οποίους περνάει το ποντίκι, δηλαδή όταν περνάει πάνω από την κάθε μπάλα. Επίσης, τροποποιήθηκαν τα αρχεία "index.html" και "style.css", προσθέτοντας αναφορές για τον κώδικα και την τοποθεσία όπου θα εμφανίζονται οι εικόνες. Επίσης, γράφτηκε κώδικας στο αρχείο "index.html" του κοινού αποθετηρίου του κώδικα για την εμφάνιση της εικόνας προφίλ μου και του username μου με κίνηση.

* Προσθήκη δυναμικής εμφάνισης εικόνων δορητών πάνω από τους οποίους περνάει το ποντίκι  
[chart.js](https://github.com/p15zach1/D3js-uk-political-donations/blob/gh-pages/chart.js)  
[index.html](https://github.com/p15zach1/D3js-uk-political-donations/blob/gh-pages/index.html)  
[style.css](https://github.com/p15zach1/D3js-uk-political-donations/blob/gh-pages/style.css)  

* Εμφάνιση των στοιχείων μου (username: p15zach1, avatar) με κάποια κίνηση στην [ιστοσελίδα](https://ioniodi.github.io/D3js-uk-political-donations/participants/) με τους φοιτητές της άσκησης, τροποποιώντας το αρχείο [index.html](https://github.com/ioniodi/D3js-uk-political-donations/blob/master/participants/index.html) στο κοινό αποθετήριο του κώδικα

## Ενδεικτικές Οθόνες:  
Αλλαγή χρωμάτων  
![new bitmap image](https://user-images.githubusercontent.com/22659306/39828446-af5e9416-53c3-11e8-9bf8-5307c57e0c57.jpg)  
  

![new bitmap image 4](https://user-images.githubusercontent.com/22659306/39828476-d1d8eb4a-53c3-11e8-82a8-74d944f2de4f.jpg)  
![new bitmap image 2](https://user-images.githubusercontent.com/22659306/39828469-cdf219ca-53c3-11e8-83b2-d59944d86f99.jpg)  
![new bitmap image 3](https://user-images.githubusercontent.com/22659306/39828473-cf1c7430-53c3-11e8-975a-98c6b40a33fa.jpg)  
![new bitmap image 5](https://user-images.githubusercontent.com/22659306/39829561-902d5baa-53c7-11e8-9fc3-3c6e254bbe09.jpg) 


## Συμπεράσματα:  


## Bιβλιογραφία και σύνδεσμοι σε σχετικές εργασίες:  
