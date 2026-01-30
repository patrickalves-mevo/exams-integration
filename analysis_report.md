# Considerações

* A busca por planos de saúde é `accent sensitive`
* Os métodos retornam `200` ou `500` dificultado a tratativa das respostas.
* Parte do retorno da API é inglês e parte é em português
* O ID do request que é retornado na criação é diferente do ID retornado quando buscamos a requisição pelo endpoint `search``
* Se a quantidade de caracteres da carteirinha estiver diferente do que é esperado, emite erro 500 sem detalhe.