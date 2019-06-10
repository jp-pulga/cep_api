# API estática de CEPs

# Consultar CEP
Basta realizar um `GET` na url `https://raw.githubusercontent.com/Pulgovisk/cep_api/master/api/v1/cep/{cep}`

Exemplo:
https://raw.githubusercontent.com/Pulgovisk/cep_api/master/api/v1/cep/01001000

Retorno:
```JSON
{
  "cep": "01001-000",
  "logradouro": "Praça da Sé",
  "complemento": "lado ímpar",
  "bairro": "Sé",
  "localidade": "São Paulo",
  "uf": "SP",
  "unidade": "",
  "ibge": "3550308",
  "gia": "1004"
}
```
