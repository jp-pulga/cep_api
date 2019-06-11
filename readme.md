# API estática de CEPs

# Consulta por CEP
Basta realizar um `GET` na url `https://raw.githubusercontent.com/Pulgovisk/cep_api/master/api/v1/cep/{cep}`

Exemplo:
https://raw.githubusercontent.com/Pulgovisk/cep_api/master/api/v1/cep/36596000

Retorno:
```JSON
{
    "bairro": "Estevão de A",
    "cep": "36596000",
    "cidade": {
        "estado": {
            "nome": "Minas Gerais",
            "sigla": "MG"
        },
        "nome": "Araponga"
    },
    "ibge": 3103702
}
```

# Consultar por Código IBGE
Basta realizar um `GET` na url `https://raw.githubusercontent.com/Pulgovisk/cep_api/master/api/v1/cod_ibge/{cep}`

Exemplo:
https://raw.githubusercontent.com/Pulgovisk/cep_api/master/api/v1/cod_ibge/3103702

Retorno:
```JSON
{
    "bairro": "Estevão de A",
    "cep": "36596000",
    "cidade": {
        "estado": {
            "nome": "Minas Gerais",
            "sigla": "MG"
        },
        "nome": "Araponga"
    },
    "ibge": 3103702
}
```

Lembrando que caso o CEP/Código IBGE não exista na base o github retorna o código 404
