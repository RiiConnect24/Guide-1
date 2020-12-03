---
title: "Συνέχεια στην εγκατάσταση του καναλιού Homebrew και του BootMii"
---

{% include toc title="Table of Contents" %}

Εάν χρειάζεστε οποιαδήποτε βοήθεια όσο αφορά αυτόν τον οδηγό, παρακαλώ μπείτε στον [RiiConnect24 διακομιστή Discord](https://discord.gg/b4Y7jfD) (προτείνεται) ή [στείλτε μας e-mail στη διεύθυνση support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![Εικονίδιο HBC](/images/hbc.png)

Το κανάλι Homebrew είναι αυτό που ανοίγει εφαρμογές Homebrew. Το BootMii είναι ένα πακέτο λογισμικού που μπορεί να κάνει αντίγραφο ασφαλείας και να επαναφέρει τον αποθηκευτικό χώρο NAND του Wii σας, και εάν εγκατασταθεί στο boot2, προσφέρει και προστασία από brick.

#### Οδηγίες

1. Θα δείτε ένα μήνυμα προειδοποίησης για scam. Περιμένετε 30 δευτερόλεπτα για να εμφανιστεί το κείμενο "Press 1 to continue", και μετά πατήστε το 1. ![Οθόνη Scam](/images/Wii/ScamScreen.png)

2. Όταν είστε στο πρόγραμμα εγκατάστασης HackMii, μπορείτε να εγκαταστήσετε το κανάλι Homebrew και το BootMii. ![Αποτελέσματα](/images/Wii/Results.png)

3. Πατήστε Continue, μετά επιλέξτε το Homebrew Channel, και πατήστε εγκατάσταση. ![Εγκαταστήσετε το Κανάλι Homebrew](/images/Wii/InstallHomebrewChannel.png)

4. Πατήστε Continue όταν τελειώσει. ![Επιτυχία Εγκατάστασης του Καναλιού Homebrew](/images/Wii/SuccessHBC.png)

5. Μόλις εγκατασταθεί, πατήστε back και πηγαίνετε στο BootMii.
6. Εάν η αρχική οθόνη γράφει ('you can install as boot2') δηλαδή ότι μπορεί να εγκατασταθεί ως boot2 κάντε το. Αυτό σας δίνει ένα επίπεδο προστασίας από brick διότι φορτώνει ως μέρος της διεργασίας του boot (εκκίνησης) του Wii σας, οπότε σας επιτρέπει να ανοίξετε κάποιο homebrew ώστε να φτιάξετε το brick ή να επαναφέρετε το Wii σας από ένα αντίγραφο ασφαλείας NAND.
7. Εάν δεν γράφει you can install as boot2, εγκαταστήστε το ως IOS (install as IOS). While this doesn't give you any brick protection, you will still be able to make a NAND backup.

![Εγκατάσταση του BootMii](/images/Wii/InstallBootMii.jpg)

8. Once done, select `Continue`, and then select `Exit` to go to the Homebrew Channel

[Continue to making a NAND Backup using BootMii](bootmii) Making a NAND backup with BootMii at this point is highly recommended.
{: .notice--info}
