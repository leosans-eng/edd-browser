# Era dos Deuses

Port para o navegador do jogo *Era dos Deuses* (RPG Maker 2000), executado pelo [EasyRPG Player](https://easyrpg.org/player/).

O jogo abre direto em `index.html`. No GitHub Pages, a página do repositório é o jogo.

**Controles:** setas para mover, Enter ou Espaço para confirmar, Esc para cancelar, Shift para correr. 

O save fica no armazenamento do navegador.

## Como o projeto funciona

A pasta `games/default` é o jogo (mapas, banco de dados e gráficos). O executável original do RPG Maker (`RPG_RT.exe`) e o instalador de Windows não entram: quem interpreta o jogo no navegador é o EasyRPG.

`RPG_RT.ini` pede a codificação Windows-1252, que é a do texto em português. `EasyRPG.ini` fixa o motor em RPG Maker 2000.

O player (arquivos `index.html`, `index.js` e `index.wasm`) é o build web oficial:

[https://easyrpg.org/downloads/player/latest/easyrpg-player-latest-js.tar.gz](https://easyrpg.org/downloads/player/latest/easyrpg-player-latest-js.tar.gz)

O código-fonte do EasyRPG Player está em [https://github.com/EasyRPG/Player](https://github.com/EasyRPG/Player) (GPL-2.0-or-later).

## Créditos

*Era dos Deuses* é um freeware de Marcos Côrtes (Planeta Software). A licença que acompanha o jogo, em `games/default/help`,  não autoriza venda nem redistribuição em massa. Este projeto não tem quaisquer fins lucrativos, nem afiliação com o criador de *EDD*.
