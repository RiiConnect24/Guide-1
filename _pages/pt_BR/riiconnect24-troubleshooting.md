---
title: "Solução de Problemas do RiiConnect24"
---

{% include toc title="Sumário" %}

![RiiConnect24 Logo](/images/WiiRC24Logo.jpg)

Se você estiver recebendo alguns desses erros (e mais nenhum outro erro), você poderá consertar o Canal deletando seu VFF.

+ Mensagem de Descontinuado
+ NEWS/FORE000001
+ NEWS/FORE000003
+ NEWS/FORE000005
+ NEWS/FORE000099

#### Você precisará de

* [WiiXplorer](https://sourceforge.net/projects/wiixplorer/files/latest/download)

#### Pastas para Deletar

+ Forecast Channel
  + 48414645
  + 4841464a
  + 48414650

+ News Channel
  + 48414745
  + 4841474a
  + 48414750

#### Instruções

1. Abra o WiiXplorer.
1. Vá até `Start` -> `Settings` -> `Boot Settings` -> `Enable NAND write access` depois selecione `Yes` para os diálogos que aparecem na tela.
1. Aperte Voltar até que você chegue na tela de arquivos.
1. Clique no ícone com um Cartão SD azul, e selecione `NAND`.
1. Navegue até `title` -> `00010002` -> XXXXXXXX -> `data`, note que XXXXXXXX é uma das pastas acima.
1. Coloque o ponteiro do Wii em cima do arquivo `wc24dl.vff` aperte o botão + no controle e selecione `Delete`.
1. Agora tente abrir o Canal que você estava com problemas. Ele deve estar funcionando. Caso contrário, entre no nosso Discord e nós tentaremos te ajudar.

[Voltar à página de instalação do RiiConnect24](riiconnect24)
