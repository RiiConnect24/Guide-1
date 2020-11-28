---
title: "Cópia de segurança BootMii"
---

{% include toc title="Table of Contents" %}

Se necessitas de ajuda para alguma coisa relacionada a este tutorial, por favor entra no [server do RiiConnect24 no Discord](https://discord.gg/b4Y7jfD) (recomendado) ou [envia-nos um e-mail para support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![BootMii Logo](/images/bootmii.png)

Tu precisas de um **cartão SD** para criar uma cópia NAND utilizando BootMii. Se não tiveres um cartão, podes passar esta página, embora seja muito recomendado criar uma cópia.
{: .notice--warning}

Um dos destaques mais importantes do BootMii é a habilidade de copiar e restaurar o armazenamento NAND da tua Wii. Vamos ver como se executa uma cópia de segurança da NAND. Podes restaurar a partir dessa cópia para qualquer razão. Recomendamos fazer uma cópia da NAND regularmente ou antes de fazer algo arriscado para a tua consola (e se souberes o que estás a fazer, tu não farás nada arriscado).

#### Requisitos
* Um cartão SD com. pelo menos, 512MB de espaço livre

#### Instruções
Se instalaste o BootMii como boot2 no último passo, precisarás de abrir o BootMii reiniciando a consola. Salta os passos 1-2 se este for o caso.
{: .notice--info}
1. Abre o Homebrew Channel.
2. Pressiona o botão HOME, depois seleciona "Launch BootMii".
   - Não é possivel utilizar um comando Wii para navegar no BootMii. You must use the POWER and RESET buttons on your console, or a GameCube controller plugged into port 1. Para navegar entre opções, pressiona POWER na tua Wii (ou o botão direcional direito num controlador GameCube). To select an option, hit RESET on your Wii or A on your GameCube controller.
3. Select the Options button (the one with the gears).
4. Select the BackupMii button (the one with the green arrow).
- A cópia da NAND irá começar. Tu podes ver o progresso no ecrã.
- "Bad Blocks" are normal. Don't worry when you see one on a NAND backup
- After this step, it will verify the backup. While it is recommended, it can be skipped by pressing the EJECT button on your Wii.
5. Quando a cópia estiver todo completo, sai do ecrã da cópia da NAND pressionando qualquer botão.
6. Para sair do BootMii, pressiona o botão Back (aquele que tem a seta) e depois podes pressionar o botão Wii Menu ou Homebrew Channel para saires para onde quiseres.

Para restaurar a partir de uma cópia NAND do teu cartão SD, podes seguir estas instruções utilizando o RestoreMii (o botão direito a seguir ao BackupMii com uma seta vermelha).
{: .notice--info}

[Continua para a instalação do Priiloader](priiloader) Priiloader adiciona um nível de proteção para bricks, e nós recomendamos isso, especialmente se tiveres o BootMii instalado como IOS.
{: .notice--info}
