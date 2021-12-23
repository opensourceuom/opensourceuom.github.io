# Τεκμηρίωση εργασίας για ιστοσελίδα

1. Κάνετε ένα αποθετήριο στο gitlab με το username.gitlab.io.  

2. Κάνετε fork το [https://gitlab.com/opensourceuom/opensourceuom.gitlab.io](https://gitlab.com/opensourceuom/opensourceuom.gitlab.io) στο αποθετήριό σου.  

3. Αφού το στήσεις, καλό είναι να ενεργοποιήσεις την επιλογή να ενημερώνεται το αποθετήριό σου από το main. Πας **Settings > Repository > Mirroring Repositories** και εκεί προσθέτεις **https://gitlab.com/opensourceuom/opensourceuom.gitlab.io.git**, pull και τα άλλα τα αφήνεις όπως είναι. 

4. Το παίρνεις τοπικά (πχ με το [GitKraken](https://gitkraken.link/iosifidis))  

5. Οι φάκελοι που δουλεύεις:

* assets/img: Περιέχει όλες τις φωτογραφίες  
* _data/sitetext.yml: Περιέχει ΟΛΕΣ τις πληροφορίες της πρώτης σελίδας  
* _data/navigation.yml: Περιέχει τις "ονομασίες" των sections.  
* _data/style.yml: Περιέχει την δήλωση των εικόνων.  

Στον φάκελο _portfolio θα προστεθούν αρχεία που αφορούν **Τα έργα μας**.

6. Ότα τελειώσεις τις αλλαγες, κάνεις push στο αποθετήριό σου και αναμένεις να γίνουν build. Θα πρέπει να δεις να είναι διαθέσιμη σελίδα στο https://username.gitlab.io/opensourceuom.gitlab.io/

7. Αφού είναι όλα ΟΚ, τότε πας στο Merge Request. Πατάς New Merge Request. Ως Source επιλέγεις το αποθετήριό σου και το branch που δουλεύεις και μετά πατάς Compare Branches and continue. Γράφεις τις δικαιολογίες, κάνε assign κάποιον από τους 3 μας να το δεχτεί και όταν γίνει αποδοχή, τότε θα πρέπει να γίνει και build στο αποθετήριό μας.
