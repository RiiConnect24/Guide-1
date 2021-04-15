---
title: "cIOS"
---

{% include toc title="Sumário" %}

Este tutorial irá lhe ensinar a como instalar cIOS (IOS customizada). Isso é necessário caso queira jogar em USB Loaders. Alguns aplicativos homebrew podem funcionar melhor com o uso de cIOS.

![Instalador d2x cIOS](/images/cios/cIOS.png)

Se você possui um Wii Mini, instale [esta cIOS](cios-mini) então. Tentar instalar outros cIOS em um Wii mini não funcionará.
{: .notice--info}

#### Você precisará de

* Um Wii conectado à internet
* Um cartão SD ou pendrive
* [d2x cIOS Installer](/assets/files/d2x-cIOS-Installer-Wii.zip)

Certifique-se de que se você estiver usando um cartão SD, a trava de bloqueio está na posição desbloqueada. caso contrário, você não será capaz de selecionar as opções corretas no instalador
{: .notice--warning}

#### Instruções

##### Parte I - Baixando

1. Baixe o instalador d2x cIOS e extraia para a pasta `apps` no seu cartão SD ou unidade USB.
1. Insira seu Cartão SD ou USB no Wii e inicie o d2x cIOS Installer pelo Homebrew Channel.

##### Parte II - Instalando

1. Pressione continuar e defina as opções dessa forma:
```
Selecione cIOS: v10 beta52 d2x-v10-beta52
Selecione cIOS base: 57
Selecione cIOS slot: 249
Selecione cIOS version: 65535
```
![Instale cIOS 249](/images/cios/Install249.png)
1. Quando feito, pressione A duas vezes para instalar.
1. Quando a instalação for concluída, pressione A para retornar, e defina as opções dessa forma:
```
Selecione cIOS: v10 beta52 d2x-v10-beta52
Selecione cIOS base: 56
Selecione cIOS slot: 250
Selecione cIOS version: 65535
```
![Instale cIOS 250](/images/cios/Install250.png)
1. Quando feito, pressione A duas vezes para instalar.
1. Quando a instalação for concluída, pressione A para retornar, e defina as opções dessa forma:
```
Selecione cIOS: v10 beta52 d2x-v10-beta52
Selecione cIOS base: 38
Selecione cIOS slot: 251
Selecione cIOS version: 65535
```
![Instale cIOS 251](/images/cios/Install251.png)
1. Quando terminado, pressione A duas vezes para instalar e então saia.

{% capture bruh %}
Embora a maioria dos jogos deva funcionar de imediato com os padrões, alguns podem exigir o uso de um cIOS específico para funcionar ou para utilizar certos recursos dentro do jogo.<br> Os exemplos incluem:
* Usando um teclado em Animal Crossing: City Folk.
* Running SpongeBob's Boating Bash.

Uma lista mais completa (embora ainda incompleta) pode ser encontrada [**aqui**](https://wiki.gbatemp.net/wiki/Wii_cIOS_base_Compatibility_List)<br> Para alterar o cIOS usado para um jogo específico, siga estas instruções:
{% endcapture %}
<div class="notice--warning">{{ bruh | markdownify }}</div>

<button class="tablinks btn btn--large btn--primary" id="defaultOpen" onclick="openTab(event, 'usbloadergx')">USB Loader GX</button>
<button class="tablinks btn btn--large btn--info" onclick="openTab(event, 'wiiflow')">WiiFlow</button>

<div id="usbloadergx" class="blanktabcontent">
  <p spaces-before="0">
    !!crwdP_24_Pdwrc!!Selecione o jogo que não está funcionando. !!crwdP_25_Pdwrc!!Clique em Configurações. !!crwdP_26_Pdwrc!!Selecione <code>Game Load</code>. !!crwdP_27_Pdwrc!!Role para baixo até <code>Game IOS</code>. !!crwdP_28_Pdwrc!!Digite o slot do IOS para usar.
  </p>
  
  <ul>
    <li>
      Tente usar 250 ou 251, se 249 não funcionar. !!crwdP_29_Pdwrc!!Pressione ok e tente carregar o jogo.
    </li>
  </ul>
</div>

<div id="wiiflow" class="blanktabcontent">
  <p spaces-before="0">
    !!crwdP_30_Pdwrc!!Selecione o jogo que não está funcionando. !!crwdP_31_Pdwrc!!Clique no ícone de engrenagem. !!crwdP_32_Pdwrc!!Vá para cIOS e use as setas para selecionar o slot do IOS a usar.
  </p>
  
  <ul>
    <li>
      Tente usar 250 ou 251, se 249 não funcionar. !!crwdP_33_Pdwrc!!Pressione Salvar e tente carregar o jogo.
    </li>
  </ul>
</div>
##### Opções depois de completado

[Continue ao Homebrew Browser](hbb)<br> O Homebrew Browser é um bom lugar para pegar homebrew no seu Wii. A instalação é opcional.
{: .notice--info}

[Continue para a navegação do site](site-navigation)<br> Temos vários outros tutoriais que você pode gostar.
{: .notice--info}

Você agora poderá usar homebrew como o [USB Loader GX](usbloadergx) e [WiiFlow](wiiflow).
{: .notice--info}

<script>
    let tabcontent = document.getElementsByClassName("blanktabcontent");
    let tablinks = document.getElementsByClassName("tablinks");!!crwd_CB_10_BC_dwrc!!</script>

