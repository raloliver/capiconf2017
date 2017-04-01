# Habilitando HTTP/2 e Conversando com o Browser

> @MathDonizete

- HTTP/2 Server Push + WebCache API (Performance)

## HTTP2

- SPDY
- UX
- HPACK
    1. Utilização de Listas
    1. Eliminação de Redundância
    1. Segurança
- Funciona apenas em HTTPS
- Server Push: requisições de uma só vez.


## NODEJS

- Módulos: node-http2 & spdy
- Melhor usar o Spdy com Express

> Melhor usar a opção SPDY com express pra ativar o HTTP2 em sua aplicação.

## WebCache API

- Service Worker Interface
- Baseado em Promises
- Manipulação do Cache
- Escopo do Browser

## Service Worker

- Events: Install, Active, Fetch, Sync, Push, Message.
- sw-precache: CLI pra gerar os arquivos essenciais para o funcionamento do SW.