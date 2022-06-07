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
Exemplo de resposta:
```

[
    {
        "id": 23,
        "title": "Call of duty MW",
        "year": 2019,
        "price": 60
    },
    {
        "id": 65,
        "title": "Sea of thieves",
        "year": 2018,
        "price": 40
    },
    {
        "id": 2,
        "title": "Minecraft",
        "year": 2012,
        "price": 20
    }
]
    
    
   ```
##### Falha na autenticação! 401
Caso essa resposta aconteça, isso significa que aconteceu alguma falha durante o processo de autenticação da requisição. Motivos: Token inválido, token expirado.

#### Prametros
email: email do usuario cadastrado no sistema
password: senha do usuario com aquele determinado email

Exemplo:
```

{
    "email":"barbiero.iper@gmail.com",
    "password":"nodejs"
}

```

