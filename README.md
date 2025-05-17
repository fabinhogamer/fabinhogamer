# YouTube Auto Comment Bot

Este projeto é um bot do Discord que detecta notificações de novos vídeos no canal `#notificação` e comenta automaticamente nesses vídeos do YouTube com base em uma lista pré-definida de canais.

## Funcionalidades

- Monitora mensagens com links do YouTube em um canal específico.
- Verifica se o vídeo pertence a um dos canais desejados.
- Comenta automaticamente no vídeo usando a API do YouTube.
- Comentários personalizados e automáticos (opcionalmente com IA).

## Canais monitorados

- Tinocando TV  
- Investiga Pinhel  
- Giuliana Mafra  
- LocomotivaPop  
- Ciência Todo Dia

## Requisitos

- Python 3.x
- Discord bot token
- Credenciais da API do YouTube (`client_secret.json`)
- Bibliotecas Python:
  - `discord.py`
  - `google-auth`
  - `google-auth-oauthlib`
  - `google-api-python-client`
  - `openai` (opcional, para comentários com IA)

## Como usar

1. Configure suas credenciais da API do YouTube e gere o arquivo `token.pkl`.
2. Crie e configure o bot do Discord com o token correto.
3. Execute o script principal para iniciar o bot.
4. O bot irá monitorar o canal `#notificação` e comentar automaticamente nos vídeos dos canais especificados.

## Hospedagem

Você pode hospedar este bot gratuitamente em plataformas como:

- [Railway](https://railway.app/)
- [Replit](https://replit.com/)
- [Render](https://render.com/)

## Licença

Este projeto é apenas para fins educacionais.
