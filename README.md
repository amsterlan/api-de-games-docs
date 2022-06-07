# API-de-games-docs
Esta api é utilizada para xxxx coisas

## Endpoints
### GET /games
esse endpoint é responsável por retornar todos os games do banco de dados
#### Parametros
nenhum
#### Respostas
##### OK! 200
caso aconteça essa mensagem você vai receber a lista de games
##### Falha na autenticação! 401
Caso essa resposta aconteça, isso significa que aconteceu alguma falha durante o processo de autenticação da requisição. Motivos: Token inválido, token expirado.
