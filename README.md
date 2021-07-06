# API ViaCEP - PHP

O código foi feito no intuito de colaborar com a comunidade de PHP, agilzando o processo de busca. Abaixo as instruções da própria API.

https://viacep.com.br/

# Acessando o webservice de CEP
Para acessar o webservice, um CEP no formato de {8} dígitos deve ser fornecido, por exemplo: "01001000".
Após o CEP, deve ser fornecido o tipo de retorno desejado, que deve ser "json", "xml", "piped" ou "querty".

Exemplo de pesquisa por CEP:
viacep.com.br/ws/01001000/json/

# Formatos de Retorno
Veja exemplos de acesso ao webservice e os diferentes tipos de retorno:

JSON
URL: viacep.com.br/ws/01001000/json/
UNICODE: viacep.com.br/ws/01001000/json/unicode/

    {
      "cep": "01001-000",
      "logradouro": "Praça da Sé",
      "complemento": "lado ímpar",
      "bairro": "Sé",
      "localidade": "São Paulo",
      "uf": "SP",
      "ibge": "3550308",
      "gia": "1004",
      "ddd": "11",
      "siafi": "7107"
    }
            
