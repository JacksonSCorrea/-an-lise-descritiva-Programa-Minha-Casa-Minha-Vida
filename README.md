# [Análise descritiva] Programa Minha Casa Minha Vida
Este repositório hospeda um projeto para análise de alguns dados do Programa Minha Casa Minha Vida e Programa casa Verde e Amarela.

A base de dados foi obtida do Portal de Dados Abertos do Governo e pode seracessado pelo link:

https://dados.gov.br/dados/conjuntos-dados/dados-de-programas-habitacionais---sistema-de-habitao---sishab


Através do link é possível fazer o dowload da base de dados e visualizar o dicionário de dados.

Para a elaboração deste projeto os o download dos dados foi realizado no dia 19/04/2023.

Neste repositório estão disponíveis o arquivo pyynb, com o código comentado.

No código, é feita a utilização da biblioteca geopy, ao qual permite a integração com o Nominating.

Assim, foi possível fazer consultas passando o endereço como parâmetro e recebendo as coordenadas geográficas de cada como retorno, o que levou cerca de 1h para realizar, aproximadamente, 5000 consultas.

Um arquivo em formato 'xlsx' (Excel) foi gerado como backup destas informações e está disponível para download neste repositório.

Feito isso, foi possível montar um mapa de densidade, utilizando a biblioteca plotly.

Este gráfico também está disponível para download neste respositório através de um arquivo no formato 'html'

Durante o projeto, são feitas algumas análises com o intuito de fazer alguns rankeamentos como, por exemplo, empresas com maior contratações no programa, agrupadas por estado. Outro exemplo de análise é sobre os agentes financeiros com maior atuação nas contratações.
