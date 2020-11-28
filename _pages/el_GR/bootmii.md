---
title: "Αντίγραφο ασφαλείας με το BootMii"
---

{% include toc title="Table of Contents" %}

Αν χρειάζεστε βοήθεια με οτιδήποτε σχετικά με αυτό τον οδηγό, επισκεφθείτε [το RiiConnect24 Discord](https://discord.gg/b4Y7jfD) (προτείνεται) ή [στείλτε μαε e-mail στο support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![BootMii Logo](/images/bootmii.png)

You need an **SD card** to create a NAND backup using BootMii. If you do not have one, you can skip this page, although it is highly recommended to create one if you can.
{: .notice--warning}

One of BootMii's most important features is the ability to backup and restore your Wii's NAND storage. We will be going over how to perform a NAND backup. You can then restore from that backup for whatever reason. We recommend making a NAND backup regularly or before you do something risky to your console (and if you know what you're doing, you won't have to do anything risky).

#### Απαιτήσεις
* Μία κάρτα SD με τουλάχιστον 512MB ελεύθερου χώρου

#### Οδηγίες
If you installed BootMii as boot2 in the last step, you will need to launch BootMii by restarting the console. Skip steps 1-2 if this is the case.
{: .notice--info}
1. Ξεκινήστε το Κανάλι Homebrew.
2. Πατήστε το πλήκτρο HOME, και επιλέξτε "Εκκίνηση BootMii".
   - Η πλοήγηση στο BootMii δεν είναι δυνατή με τη χρήση χειριστηρίου Wii. You must use the POWER and RESET buttons on your console, or a GameCube controller plugged into port 1. Για να πλοηγηθείτε μεταξύ επιλογών, πατήστε το κουμπί POWER στο Wii σας (ή το δεξί +Σταυρό Ελέγχου στο χειριστήριο GameCube). To select an option, hit RESET on your Wii or A on your GameCube controller.
3. Select the Options button (the one with the gears).
4. Select the BackupMii button (the one with the green arrow).
- Το αντίγραφο ασφαλείας της μνήμης NAND θα ξεκινήσει. Μπορείτε να δείτε την πρόοδο στην οθόνη.
- "Bad Blocks" are normal. Don't worry when you see one on a NAND backup
- After this step, it will verify the backup. While it is recommended, it can be skipped by pressing the EJECT button on your Wii.
5. Όταν το αντίγραφο ολοκληρωθεί, βγείτε από την οθόνη αντιγράφου ασφαλείας πατώντας οποιοδήποτε κουμπί.
6. Για να βγείτε από το BootMii, επιλέξτε την επιλογή Πίσω (αυτή με το βέλος) και ύστερα μπορείτε να επιλέξετε είτε την επιλογή Μενού Wii ή την επιλογή Κανάλι Homebrew για να επιστρέψετε εκεί που επιθυμείτε.

To restore from a NAND backup on your SD card, you can follow these instructions using RestoreMii (the button right next to BackupMii with a red arrow).
{: .notice--info}

[Continue to Priiloader Installation](priiloader) Priiloader adds a level of brick protection, and we recommend it, especially if you were only able to install BootMii IOS.
{: .notice--info}
