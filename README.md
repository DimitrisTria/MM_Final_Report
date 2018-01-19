# Μάθημα: Πολυμέσα

### Ονοματεπώνυμο: Δημήτριος Τριανταφύλλου
### Αριθμός Μητρώου: Π2015077

* Link demo: [https://dimitristria.github.io/Super-Mario/](https://dimitristria.github.io/Super-Mario/ "Link demo")
* Αποθετήριο κώδικα: [https://github.com/DimitrisTria/Super-Mario/tree/gh-pages](https://github.com/DimitrisTria/Super-Mario/tree/gh-pages "Αποθετήριο κώδικα")

### Εισαγωγή
  Το παρακάτω παιχνίδι, Super Mario, δημιουργήθηκε για τα πλαίσια της εργασίας εξαμήνου του μαθήματος Πολυμέσα, του Ιόνιου Πανεπιστημίου, στο πέμπτου εξαμήνου.

### Σύνοψη
  Το παιχνίδι που δημιούργησα, βάση του κώδικα που μας δώθηκε για την εργασία ([https://github.com/ioniodi/Super-Mario](https://github.com/ioniodi/Super-Mario)), τηρεί όλες τις προϋποθέσεις για τα παραδοτέα του μαθήματος.
  Επιπλέον, επέκτεινα το παιχνίδι με προσθήκες όπως επιπλέον κουμπιών στο menu (Levels,Help,Settings), δυνατότητα σίγασης όλων των ήχων στο παιχνίδι, δυνατότητα επιλογής δυσκολίας, επιπλέον πίστες (όπως εκπαιδευτική πίστα), λειτουργία checkpoints και επιπλέον είδη bonus.

### Επιλογή εργαλείων
  * Λογισμικό ολοκληρωμένου περιβάλλοντος προγραμματισμού: Visual Studio Code [https://code.visualstudio.com/](https://code.visualstudio.com/ "Visual Studio Code")
  * Λογισμικό επεξεργασίας εικόνων: Paint.Net [https://www.getpaint.net/](https://www.getpaint.net/ "Paint.Net")
  * Λογισμικό δημιουργία επιπέδων στο παιχνίδι: Tiled [http://www.mapeditor.org/](http://www.mapeditor.org/ "Tiled")

### Διαδικασία ανάπτυξης
  Αρχικά, μετά από την επιλογή του θέματος χρησιμοποίησα ένα περιβάλλον προγραμματισμού της επιλογής μου και συγκεκριμένα το Visual Studio Code. Ο λόγος για αυτό είναι το ότι, έχω τη δυνατότητα να τρέξω τον κώδικα εκτός διαδυκτίου και με σαφως μεγαλύτερη απόδοση και ταχύτητα τοπικά στο σύστημα που χρησιμοποιώ. Αργότερα, για να αναπτύξω τον κώδικα, για την υλοποίηση των παραδοτέων, χρησιμοποίησα ως πηγές τους ακόλουθους συνδέσμους για εκμάθηση javascript ([https://www.javascript.com/learn/javascript/strings](https://www.javascript.com/learn/javascript/strings 'javascript tutorials')) και της μηχανής παιχνιδιού (game engine) Phaser ([https://phaser.io/examples](https://phaser.io/examples 'Phaser examples')). Με μια μικρή αναζήτηση στο διαδίκτυο ενημερώθηκα με συμβουλές για την ανάπτυξη ενός παιχνιδιού ([http://www.creativebloq.com/inspiration/10-tips-building-better-game-5126304](http://www.creativebloq.com/inspiration/10-tips-building-better-game-5126304 '10 tips for building a better game')).

### Ενδεικτικές οθόνες

#### ***I) Μenu στην αρχή του παιχνιδιού***

  ![menu](https://user-images.githubusercontent.com/22676085/33654136-deb9c26e-da77-11e7-8ea8-ee64186b5470.png)

i) Πρώτο κουμπί: **Play**

  Ξεκινάει το παιχνίδι από τη πρώτη πίστα, η οποία είναι και tutorial πίστα.

ii) Δεύτερο κουμπί: **Levels**

  Επιλογή πίστας από το χρήστη επιλέγωντας τον αριθμό της πίστας, το οποίο συνδιάζεται και με ενδεικτική εικόνα με την επιλεγούμενη πίστα, και μετά το κουμπί play.

  ![levels](https://user-images.githubusercontent.com/22676085/33654133-de443a8a-da77-11e7-8212-c2ecb8c75dae.png)

  Επιπλέον, στις πίστες εφαρμόζεται και σύστημα διαχείρησης επιπέδων, όπου μετά την επιτυχή ολοκλήρωση του προηγούμενου επιπέδου γίνεται διαθέσιμο το επόμενο. Γίνεται χρήση χρωμάτων πράσινο και κόκκινο για την ένδειξη διαθεσιμότητας του επιπέδου.

  1) Με την επιλογή πράσινου πλαισιού (διαθέσιμη πίστα) γίνεται προβολή στιγμιοτύπου της πίστας που επιλέχθηκε.

   ![levels_unlocked](https://user-images.githubusercontent.com/22676085/33654135-de938536-da77-11e7-9e5d-1d135a272ef3.png)

  2) Με την επιλογή πράσινου πλαισιού (μη διαθέσιμη πίστα) δε γίνεται προβολή στιγμιοτύπου της πίστας που επιλέχθηκε.

   ![levels_locked](https://user-images.githubusercontent.com/22676085/33654134-de6ba0de-da77-11e7-9ceb-bf56e1faaa14.png)

iii) Τρίτο κουμπί: **Help**

  Περιέχει οδηγίες για το χειρισμό του παίκτη.

  ![help](https://user-images.githubusercontent.com/22676085/35142631-7e36097c-fd07-11e7-9c0f-ca9a25fe8594.png)

iv) Τέταρτο κουμπί: **Settings**

  1) Κουμπί για επιλογή σίγασης των ήχων.

  2) Κουμπί για επιλογή δυσκολίας.

    Normal: Αρχικές ζωές πέντε (5) και με την επιτυχή ολοκλήρωση μιας πίστας αυξάνονται κατά μία (1).
    
    Hard: Πέντε (5) ζωές σε όλο το παιχνίδι και η ταχύτητα μετακίνησης των εχθρών έχει διπλασιαστεί (x2).
    
    Survival: Μία (1) ζωή σε όλο το παιχνίδι.

  ![settings](https://user-images.githubusercontent.com/22676085/33654138-df1515b0-da77-11e7-9a66-8713219ceb94.png)

#### ***II) Πίστες του παιχνιδιού***

i) Πρώτη πίστα η οποία είναι και εκπαιδευτική πίστα

  ![super_mario_map0](https://user-images.githubusercontent.com/22676085/33488606-d811c7fc-d6b9-11e7-96f5-327a5e12046b.png)

ii) Δεύτερη πίστα

  ![super_mario_map1](https://user-images.githubusercontent.com/22676085/33655905-1ed91048-da7d-11e7-8953-220805da2b54.png)

iii) Τρίτη πίστα

  ![super_mario_map2](https://user-images.githubusercontent.com/22676085/33656042-8c4bb996-da7d-11e7-97db-7063614cf673.png)

iv) Τέταρτη πίστα

  ![super_mario_map3](https://user-images.githubusercontent.com/22676085/33655704-7fce8c08-da7c-11e7-850e-ef5d0cfd1925.png)

#### ***ΙΙΙ) Χαρακτήρες στο παιχνίδι***

i) Παίκτης (1)

  ![player](https://user-images.githubusercontent.com/22676085/32542777-5ba8b378-c47c-11e7-9f01-6705d5a01311.png)

ii) Εχθροί (3)

  1) Eχθρός που κινείται στη πίστα.
  
   Goomba: ![goomba](https://user-images.githubusercontent.com/22676085/34834252-41c0dd4a-f6fa-11e7-962c-b9afde307604.png)

  2) Νέος εχθρός που κινείται αιωρούμενος στη πίστα. Συγκεκριμένα όπου βρεί εμπόδιο αλλάζει την κατεύθυνσή του και είναι απέθαντος.
    
   Fireball: ![fireball](https://user-images.githubusercontent.com/22676085/33483734-e4f7be20-d6a7-11e7-8b42-866793675d33.png)

  3) Νέος εχθρός που βρίσκεται στον αέρα σε σημεία στη πίστα και πυροβολά τον παίκτη τακτικά όταν αυτός βρίσκεται στην περιοχή επίθεσής του και είναι απέθαντος.
    
   UFO: ![ufo](https://user-images.githubusercontent.com/22676085/33483697-be8a3740-d6a7-11e7-8931-bf77ccdfd3cc.png)

#### ***IV) Επέκταση του παιχνιδιού***

i) Δυνατότητα τηλεμεταφοράς του παίκτη σε κάποιο σημείο της πίστας πέρα από αυτό που βρίσκεται αυτή τη στιγμή.Ο παίκτης για να ενεργοποιήσει τη λειτουργία teleport στη πίστα χρειάζεται να συλλέξει το αντικείμενο: ![teleport](https://user-images.githubusercontent.com/22676085/33485137-f60c9cc0-d6ad-11e7-8207-570955ef6da2.png) από το αντικείμενο: ![bonus box](https://user-images.githubusercontent.com/22676085/33485200-28de6f84-d6ae-11e7-9666-adaacb6125a3.png).

ii) Πόντοι, Μπόνους, Ζωές
  ![score_bonus_lifes](https://user-images.githubusercontent.com/22676085/34834756-8178f2dc-f6fb-11e7-809b-1263047acb21.png)

  1) Πόντοι (score) παίκτη
    
    -> μείον πέντε (-5) πόντους όταν χάνει κάποια ζωή ο παίκτης.
    -> δέκα (10) πόντοι για συλλογή νομίσματος
    -> δέκα πέτε (15) πόντοι για το πάτημα ενός goomba.
  
  2) Μπόνους (bonus) παίκτη
  
   Το μπόνους του παίκτη επιτυγχάνεται με το να συλλέξει το μανητάρι: από το αντικείμενο: . Η επίδραση ττου είναι για σύντομο χρονικό διάστημα και πιο συγκεκριμένα οκτώ (8) δευτερόλεπτα.
    
    -> αόρατος
    -> διπλό score στα νομίσματα
    -> διπλό score στα kills.
  
  3) Ζωές παίκτη
    
    -> πέντε (5) ζωές συνολικά στο παιχνίδι.
  
  * Οι ζωές του παίκτη εξαρτώνται και από την επιλογή δυσκολίας, αλλά συνολικά μπορεί να έχει εως πέντε (5).
  
iii) Ήχοι και μουσική

  1) Προσθήκη νέων ήχων από το αυθεντικό Super Mario Bros.
  2) Προσθήκη μουσικής για στο παιχνίδι.
  
### Πηγές πολυμεσικού υλικού που χρησιμοποιήθηκε στο παιχνίδι
  
  * menu background: [http://iliketowastemytime.com/2012/12/30/daily-wallpaper-star-map](http://iliketowastemytime.com/2012/12/30/daily-wallpaper-star-map 'menu background')
  * gameplay background: [https://i.pinimg.com/originals/84/b7/ab/84b7abce44bcca4c0b6f203cd3a467e4.jpg](https://i.pinimg.com/originals/84/b7/ab/84b7abce44bcca4c0b6f203cd3a467e4.jpg 'gameplay background')
  * Super Mario Bros: [https://scratch.mit.edu/projects/49905542/](https://scratch.mit.edu/projects/49905542/ "Super Mario Bros")
  * freesound: [https://freesound.org/](https://freesound.org/ "freesound")
  * Super Mario Bros assets1: [https://www.spriters-resource.com/nes/supermariobros2supermariobrosthelostlevelsjpn/sheet/52630/](https://www.spriters-resource.com/nes/supermariobros2supermariobrosthelostlevelsjpn/sheet/52630/ 'Super Mario Bros assets1')
  * Super Mario Bros assets2: [http://www.nesmaps.com/maps/SuperMarioBrothers/sprites/SuperMarioBrothersSprites.html](http://www.nesmaps.com/maps/SuperMarioBrothers/sprites/SuperMarioBrothersSprites.html 'Super Mario Bros assets2')
  * coin animation: [http://s11.postimg.org/p9sml5v4z/Coins.png](http://s11.postimg.org/p9sml5v4z/Coins.png 'coin animation')
  * firework animation: [https://giphy.com/stickers/free-fireworks-clipart-vzF0lrwPoR9kc?utm_source=media-link&utm_medium=landing&utm_campaign=Media%20Links&utm_term=https://www.google.co.in/](https://giphy.com/stickers/free-fireworks-clipart-vzF0lrwPoR9kc?utm_source=media-link&utm_medium=landing&utm_campaign=Media%20Links&utm_term=https://www.google.co.in/ 'firework animation')
  * teleport sprite: [https://itunes.apple.com/us/app/iteleport-vnc-rdp/id489094439?mt=12](https://itunes.apple.com/us/app/iteleport-vnc-rdp/id489094439?mt=12 'teleport sprite')
  * player and fireball sprites: [https://opengameart.org/content/16x16-16x24-32x32-rpg-enemies-updated](https://opengameart.org/content/16x16-16x24-32x32-rpg-enemies-updated 'player and fireball sprites')
  * help arrows: [http://www.101computing.net/wp/wp-content/uploads/arrowKeys-300x205.png](http://www.101computing.net/wp/wp-content/uploads/arrowKeys-300x205.png)
  
  Το υπόλοιπο πολυμεσικό περιεχόμενο, εκτός από αυτά που ήρθαν με το παιχνίδι στην εργασία, δημιουργήθηκαν από εμένα.

### Συμπεράσματα

