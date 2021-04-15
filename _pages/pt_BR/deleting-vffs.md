---
title: "Deletando VFFs"
---

{% include toc title="Table of Contents" %}

Se você precisa de ajuda sobre qualquer coisa deste tutorial, por favor entre [no servidor do Discord RiiConnect24](https://discord.gg/rc24) (recomendado) ou [mande um e-mail para support@riiconnect24.net (em inglês)](mailto:support@riiconnect24.net).
{: .notice--info}

![RiiConnect24 Logo](/images/WiiRC24Logo.jpg)

If you're getting one of these errors (and not any other error), you should be able to fix the Channel by deleting your VFF.

+ Discontinued Message
+ NEWS/FORE000001
+ NEWS/FORE000003
+ NEWS/FORE000005
+ NEWS/FORE000099

#### Você precisará de
* Um cartão SD ou pendrive
* [WiiXplorer](https://sourceforge.net/projects/wiixplorer/files/latest/download)

#### Folder to Delete

+ Forecast Channel
  + 48414645
  + 4841464a
  + 48414650

+ News Channel
  + 48414745
  + 4841474a
  + 48414750

#### Instruções

1. Launch WiiXplorer.
2. Go to `Start` -> `Settings` -> `Boot Settings` -> `Enable NAND write access` and then select `Yes` for both dialogues that appear on the screen.
3. Press Back until you have reached the file explorer screen.
4. Select the tiny blue SD Card icon, then select `NAND`.
5. Navigate to `title` -> `00010002` -> XXXXXXXX -> `data`, where XXXXXXXX is one of the folders above.
6. Hover over `wc24dl.vff` and press the + button and select `Delete`.

Try to launch the Channel you were having trouble with now.

[Return to RiiConnect24 installation page](riiconnect24)
{: .notice--info}
