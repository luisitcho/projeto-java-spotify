# projeto-java-spotify
API do Spotify em Java com Spring Open Feign.

Baseado no vídeo:
https://www.youtube.com/watch?v=zQKrgXsZFSE

Documentação utilizada:
https://developer.spotify.com/documentation/web-api/reference/get-users-top-artists-and-tracks

Sobre o projeto:
Este projeto demonstra como consumir a API do Spotify utilizando Java,
Spring Boot e Spring Open Feign, realizando chamadas autenticadas via OAuth 2.0.

Endpoint principal estudado:
/me/top/{type}

Exemplo:
GET https://api.spotify.com/v1/me/top/artists
Authorization: Bearer {token}

Parâmetros comuns:
- type: artists ou tracks
- time_range: long_term, medium_term, short_term
- limit: quantidade de itens (máx 50)
- offset: paginação

Requisitos:
- Ter uma aplicação criada no Spotify Developer Dashboard.
- Possuir um Access Token com o scope: user-top-read.
