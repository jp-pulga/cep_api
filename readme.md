# API estática de CEPs

# Consultar CEP
Basta realizar um `GET` na url `https://raw.githubusercontent.com/Pulgovisk/cep_api/master/api/v1/cep/{cep}`

Exemplo:
https://raw.githubusercontent.com/Pulgovisk/cep_api/master/api/v1/cep/01001000

Retorno:
```JSON
{
  "cep": "01001000",
  "logradouro": "Praça da Sé lado ímpar",
  "bairro": "Sé",
  "cidade": {
    "nome": "São Paulo",
    "estado": {
      "nome": "São Paulo",
      "sigla": "SP"
    }
  }
}
```
