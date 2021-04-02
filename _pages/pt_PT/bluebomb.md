---
title: "BlueBomb"
---

{% include toc title="Table of Contents" %}

Se tu precisas de ajuda com alguma coisa relacionada a este tutorial, por favor entra no [server Wii Mini Hacking no Discord](https://discord.gg/6ryxnkS) (recomendado)
{: .notice--info}

![BlueBomb](/images/bluebomb.png)

BlueBomb é um exploit que tira proveito de uma falha nas bibliotecas Bluetooth da Wii e da Wii Mini. Apesar de ser o único exploit que funciona para o Wii Mini, BlueBomb também funciona na Wii original. Este exploit também ativa a recuperação de certos bricks, como os bricks de banner.

Para a Wii original, nós não recomendamos a utilização do BlueBomb se pretendes instalar o Homebrew Channel e BootMii, já que há mais exploits disponíveis para isso.
{: .notice--info}

#### Secção I - O que precisas
- Uma máquina Linux
  - Se tens um Raspberry Pi, podes utilizá-lo, já que ele tem o Linux pré-instalado.
  - O Subsistema Windows para Linux *não funcionará* já que este não tem acesso direto ao adaptador Bluetooth ou entradas USB.
  - Se tu não tiveres Linux, [Ubuntu](https://ubuntu.com/download/desktop) é a melhor opção e pode ser executado em computadores que utilizam Windows ou macOS.
    - Dispositivos de 32-bit requerem [Ubuntu 16.04](http://releases.ubuntu.com/16.04/).
    - Para dispositivos 64-bit é recomendado que utilizes a edição LTS devido à estabilidade, mas a versão mais recente também funciona.
  - Tu podes [instalar Linux num USB flash drive](https://ubuntu.com/tutorials/tutorial-create-a-usb-stick-on-windows#1-overview) em vez de instalá-lo no teu computador.
- Um adaptador Bluetooth.
  - Um adaptador Bluetooth interno funcionará.
  - Se não tiveres um, certifica-te que arranjas um com compatibilidade com Linux.
- Um USB flash drive formatado como FAT32.
  - Isto não pode ser o mesmo flash drive utilizado para a tua máquina Linux.

#### Secção II - Executar o exploit
1. Descarrega o instalador HackMii a partir do [site do BootMii](https://bootmii.org/download/).
- (Se estiveres a corrigir um brick, tu também podes copiar a aplicação homebrew que desejas utilizar em /apps/)
1. Extract it and place the `boot.elf` file in your flash drive.
1. Conecta o flash drive na consola. Para a Wii Mini, a entrada USB está na parte de trás. Para a Wii normal, utiliza a entrada debaixo. (ou a entrada da direita se estiver de pé).
1. Liga a tua consola e navega até ao menu das definições. No canto superior direito verás um código de 4 caracteres como o da imagem abaixo. Este código é a tua versão do Wii Menu, anota isso já que irás precisá-lo mais tarde. Depois disso, desliga a tua consola. ![SystemMenuVersion](/images/Wii/SystemMenuVersion.png)
1. Inicia a tua distribuição do Linux, e certifica que estás conectado à internet.
1. Abre o Terminal
1. Executa os seguintes comandos:
```bash
wget https://wii.guide/assets/files/bluebomb-helper.sh
chmod +x bluebomb-helper.sh
./bluebomb-helper.sh
```
1. O ajudante descarregará os ficheiros necessários; e perguntará por informações sobre a tua consola.
  - Se tu selecionaste a Wii Mini, serás solicitado a fornecer a tua região. Isto pode ser determinado pela ultima letra da versão do Wii Menu (`U` para **EUA** e `E` para modelos ** PAL**).
  - Se selecionaste a Wii serás solicitado a fornecer a tua versão do Wii Menu (O que anotaste no passo 4)
1. Turn on your console and **do not** connect any Wii Remotes.
1. Pressiona o botão Sync repetidamente até ao terminal mostrar `got connection handle`. Poderá levar a numerosas tentativa, por isso não desistas.

Certifica-te que a consola está perto do computador a executar o exploit, de preferência a menos de 1 metro.
{: .notice--info}

Agora a consola deverá abrir o instalador HackMii. Agora podes desligar o teu computador Linux se não planeares utilizá-lo mais tarde.

[Se estiveres a utilizar a Wii, procede para a instalação do Homebrew Channel e BootMii](hbc)
{: .notice--info}

[Se estiveres a utilizar uma Wii Mini, procede à instalação do Homebrew Channel](hbc-mini)
{: .notice--info}
