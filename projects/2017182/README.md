# Προσωπικά Στοιχεία

## Νέμανια Γιέβτιτς
## AM : π2017182

[Github profile](https://github.com/IonianIronist)

| Εβδομάδα | [Όλα τα παραδοτέα βρίσκονται στην ίδια σελίδα της τελικής αναφοράς](https://epidrome.github.io/teaching/deliverables/) με τα προσωπικά στοιχεία σας (Όνομα, ΑΜ, github profile) και μαζί με αυτόν εδώ τον πίνακα περιεχομένων | Σύνδεσμος στην [εβδομαδιαία παρουσίαση προόδου στις συζητήσεις](https://github.com/courses-ionio/help/discussions/categories/show-and-tell) | Αυτοαξιολόγηση σύμφωνα με τα κριτήρια της αντίστοιχης άσκησης |
| --- | --- | --- | --- |
| 1 | [Δημιουργία ομάδας](https://epidrome.github.io/teaching/team/) + [Φορκ και δημιουργία σελίδας τελικής αναφοράς](https://epidrome.github.io/teaching/guide/), [προσθήκη πίνακα περιεχομένων](https://raw.githubusercontent.com/courses-ionio/sw/master/README.md), [συγγραφή της εισαγωγής](https://epidrome.github.io/teaching/intro/), αποστολή της εισαγωγής [για σχολιασμό στην συζήτηση](https://github.com/courses-ionio/sw/discussions/categories/show-and-tell) και καταγραφή του συνδέσμου συζήτησης δίπλα --> | [link](https://github.com/courses-ionio/sw/discussions/1620) | Άργησα να ξεκινήσω (ισχύει και για τα υπόλοιπα παραδοτέα), κατά τα άλλα κάνω μια γενική τοποθέτηση για τις γενικές προσδοκίες μου |
| 2 | [Γραμμή εντολών](https://epidrome.github.io/teaching/cli) (systemd) και [διαδικασία συνεργασίας με pull request στον οργανισμό της ομάδας σας](https://epidrome.github.io/teaching/team) | | |
| 3 | Γραμμή εντολών (no systemd) | | |
| 4 | Κατασκευή του βιβλίου Α2 (συνεργατικά) | | |
| 5 | Συμμετοχικό περιεχόμενο A1 + A2 | | |
| 6 | Γραμμή εντολών (no systemd, custom static blog generator) | | |
| 7 | συμμετοχικό περιεχόμενο B1 | | |
| 8 | Κατασκευή του βιβλίου Β2 (συνεργατικά) | | |
| 9 | συμμετοχικό περιεχόμενο B2 | | |
| 10 | Τελική αναφορά* | | |

## 1) Εισαγωγή

Με το πέρας του μαθήματος θα ήθελα να είμαι πιο εξοικειωμένος με τις τεχνολογίες ανάπτυξης και οργάνωσης λογισμικού, καθώς και με περιβάλλοντα βασιμένα σε GNU/Linux. 
Εργαζόμενος ως fullstack developer τα τελευτάια 2 χρόνια έχω παρατηρήσει μεγάλη αύξηση της παραγογικότητάς μου από την στιγμή που έχω μεταφέρει το develompent environment μου
σε λίνουξ (insert I use arch btw meme here) και ειδικότερα με την χρήση των εργαλείων που δεν υπάρχουν ή χρησιμοποιούνται σπανίως στα Windows.
Αυτήν την στιγμή τα κεντρικά εργαλεία που χρησιμοποιώ για την ανάπτυξη λογισμικού είναι:
  - [awesomewm](https://awesomewm.org/) - ένα window manager ανοιχτού κώδικα γραμμένο σε lua,
το οποίο το [έχω προσαρμόσει](https://github.com/IonianIronist/configs/tree/main/awesome) ώστε να τεριάζει στις ανάγκες μου
  - [tmux](https://github.com/tmux/tmux/wiki) - o GNU terminal multiplexer, που κάνει θαύματα ώστε όλοι οι σέρβερς μου και τα ξεχωριστά πρότζεκτ που πρέπει να τρέχουν μαζί να είναι οργανομένα και εύκολα προσβάσιμα. Έχω ένα μικρό [config](https://github.com/IonianIronist/configs/tree/main/tmux) και γι αυτό.
  - [neovim](https://neovim.io/) - Μάλλον το πιο σημαντικό κομμάτι του μικρού αυτού στακ που πλέον χωρίς αυτό δεν ζω. [config](https://github.com/IonianIronist/configs/tree/main/nvim)
  
 Έχοντας πει αυτά, σκοπός μου είναι να εξελίξω περισσότερο τις γνώσεις μου όσο αφορά τα συνηθισμένα workflows που χρησιμοποιούνται κατά την ανάπτυξη εφαρμογών, από το development μέχρι το
 deployment, καθώς και να εξοικειωθώ ακόμα καλύτερα με το σύστημά μου και να καταφέρω να υλοποιήσω κάποιες βελτιώσεις όπου αυτό είναι δυνατό.

# 2) Γραμμή εντολών - create an agent for news

Για το δεύτερο task αποφάσησα να βασιστώ στο [newsboat](https://github.com/newsboat/newsboat) ώστε να μπορώ να διαβάζω το rss feed μου μέσω ενός προγράμματος τερματικού (παλιότερα χρησιμοποιούσα το [fluentreader](https://github.com/yang991178/fluent-reader/)).
Από μόνο του το newsboat δίνει μια καλή βάση σε αυτό που ήθελα αλλά δεν είχε την δυνατότητα προβολής του κύριου σώματος των άρθρων μέσα από το πρόγραμμα χωρίς παραπάνω configuration.
Από default με την εντολή open article το πρόγραμμα προσπαθεί να ανοίξει το browser. Για να κρατήσω όλη την διαδικασία στο τερματικό έκανα την εξίς προσθήκη στο config:

```
browser "python -m readability.readability -u %u 2> /dev/null 1 | w3m -dump -T text/html | less"
```

Ουσιαστικά το newsboat πλέον με το 'open in browser' θα τρέχει την παραπάνω εντολή, η οποία χρησιμοποιεί την python βιβλιοθήκη [readability-lxml](https://pypi.org/project/readability-lxml/) για να καθαρίσει το html από ό,τι δεν είναι το κύριο σώμα του άρθρου (λίνκς, μενού, υπόλοιπο περιεχόμενο της σελίδας), το κάνει pipe στο [w3m](https://w3m.sourceforge.net/) το οποίο αφαιρεί όλα τα tags κλπ και στην συνέχεια το καθαρό κείμενο γίνεται pipe στο less για να διαβαστεί τελικά από τον χρήστη.

Πέραν απ αυτό επειδή παρατήρησα στον .newsboat φάκελο ότι υπάρχει μια sqlite3 βάση η οποία περιέχει τα κασαρισμένα άρθρα είπα να το κάνω λίγο ενδιαφέρον και έγραψα και ένα [python σκριπτάκι](https://gist.github.com/IonianIronist/bbce13d36da8ae5ca083048bc7d40b4b) για να μπορώ να βλέπω γρήγορα χωρίς να ανοίγω tui του προγράμματος αν υπάρχουν καινούρια άρθρα που δεν έχω διαβάσει και πόσα, και ποιό είναι το τελευταίο άρθρο που έχει ανέβει και πότε. 

[asciinema recording](https://asciinema.org/a/psluSghQnLrikn29KGpHnuozx)
