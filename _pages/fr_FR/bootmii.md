---
title: "Sauvegarde BootMii"
---

{% include toc title="Table des matières" %}

Si vous avez besoin d'aide pour quoi que ce soit concernant ce didacticiel, veuillez rejoindre [ le serveur RiiConnect24 Discord ](https://discord.gg/rc24) (recommandé) ou \[ envoyez-nous un e-mail à support@riiconnect24.net \](mailto: support @ riiconnect24 .net).
{: .notice--info}

![BootMii Logo](/images/bootmii.png)

Vous avez besoin d'une ** carte SD ** pour créer une sauvegarde NAND à l'aide de BootMii. Si vous n'en avez pas, vous pouvez sauter cette page, bien qu'il soit fortement recommandé de créer une sauvegarde si vous le pouvez.
{: .notice--warning}

L'une des fonctionnalités les plus importantes de BootMii est la possibilité de sauvegarder et de restaurer le stockage NAND de votre Wii. Nous allons voir comment effectuer une sauvegarde (backup) de la mémoire de votre console (NAND). Vous pourrez ensuite la restaurer depuis cette sauvegarde pour une quelconque raison. C'est une bonne idée de faire une sauvegarde NAND régulièrement ou avant de faire quelque chose de risqué sur votre console (et si vous savez ce que vous faites, vous n'aurez rien à faire de risqué).

#### Ce dont vous avez besoin
* Une carte SD avec au moins 512 Mo d'espace libre

#### Instructions
1. Lancez la Chaîne Homebrew.
2. Appuyer sur le bouton HOME, et choisissez "Launch BootMii".

    La navigation dans BootMii n'est pas possible avec une télécommande Wii. Vous devez utiliser les boutons POWER et RESET de votre console, ou un contrôleur GameCube branché sur le port 1 Pour naviguer entre les options, appuyez sur POWER sur votre Wii (ou sur le bouton droit + Control Pad sur une manette GameCube). Pour naviguer entre les options, appuyez sur POWER sur votre Wii (ou sur le bouton droit + Control Pad sur une manette GameCube). Pour sélectionner une option, appuyez sur RESET sur votre Wii ou A sur votre manette GameCube.
    {: .notice--info}


    Si l'écran reste noir et que le voyant bleu du lecteur de disque clignote, il vous manque les fichiers BootMii sur votre carte SD. Téléchargez [ce zip](https://static.hackmii.com/bootmii_sd_files.zip) et extrayez le à la racine de votre carte SD, puis réessayez.
    {: .notice--warning}

3. Sélectionnez le bouton Options (celui avec les engrenages).
4. Sélectionnez le bouton BackupMii (celui avec la flèche verte).
- Une sauvegarde complète de la mémoire de la console (NAND) va démarrer. Vous pouvez voir la progression sur votre écran.
- Les "mauvais" blocks ("Bad blocks") sont normaux. Ne vous inquiétez pas si vous en voyez un lors de la sauvegarde
- Après cette étape, l'outil va procéder à une vérification de la sauvegarde. Bien qu'il soit recommandé de le faire, vous pouvez le passer en appuyant sur le bouton "EJECT" de votre console.
5. Lorsque la sauvegarde est complètement finie, quittez le menu de sauvegarde en appuyant sur n'importe quel bouton.
6. Pour quitter BootMii, appuyez sur le bouton Retour (celui avec la flèche) puis vous pouvez appuyer sur bouton Wii Menu ou celui de la Chaîne Homebrew pour retourner au menu de votre choix.


<!---
To restore from a NAND backup on your SD card, you can follow these instructions using RestoreMii (the button right next to BackupMii with a red arrow).
{: .notice--info}
-->

[ Poursuivre l'installation du Priiloader ](priiloader) Priiloader ajoute un niveau de protection de brique, et nous le recommandons, surtout si vous n'avez pu installer BootMii IOS.
{: .notice--info}
