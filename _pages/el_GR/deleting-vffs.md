---
title: "Διαγραφή VFF"
---

{% include toc title="Table of Contents" %}

If you need help for anything regarding this tutorial, please join [the RiiConnect24 Discord server](https://discord.gg/rc24) (recommended) or [e-mail us at support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![Εικονίδιο RiiConnect24](/images/WiiRC24Logo.jpg)

Εάν συμβαίνει ένα τέτοιο σφάλμα (και όχι οποιοδήποτε άλλο), λογικά μπορείτε να φτιάξετε το Κανάλι διαγράφοντας το VFF σας.

+ Μήνυμα Διακοπής Λειτουργίας
+ NEWS/FORE000001
+ NEWS/FORE000003
+ NEWS/FORE000005
+ NEWS/FORE000099

#### Τι χρειάζεστε
* Μία κάρτα SD ή μέσο αποθήκευσης USB
* [Το WiiXplorer](https://sourceforge.net/projects/wiixplorer/files/latest/download)

#### Φάκελοι προς διαγραφή

+ Κανάλι Forecast (καιρού)
  + 48414645
  + 4841464a
  + 48414650

+ Κανάλι News (ειδήσεων)
  + 48414745
  + 4841474a
  + 48414750

#### Οδηγίες

1. Ανοίξτε το WiiXplorer.
2. Πατήστε `Start` -> `Settings` -> `Boot Settings` -> `Ενεργοποιήστε το NAND write access` και μετά πατήστε `Yes` και στις δύο προειδοποιήσεις που θα εμφανιστούν στην οθόνη.
3. Πατήστε Back μέχρι να φτάσετε στην αρχική σελίδα με τα αρχεία.
4. Πατήστε το μικρό μπλε εικονίδιο με την κάρτα SD, και μετά πατήστε `NAND`.
5. Πηγαίνετε στη διαδρομή `title` -> `00010002` -> XXXXXXXX -> `data`, όπου XXXXXXXX είναι ένας από τους παραπάνω φακέλους.
6. Στοχεύστε στο `wc24dl.vff`, πατήστε το κουμπί + και πατήστε `Delete` για διαγραφή.

Προσπαθείστε τώρα να ανοίξετε το κανάλι που είχατε πρόβλημα.

[Επιστροφή στη σελίδα εγκατάστασης RiiConnect24](riiconnect24)
{: .notice--info}
