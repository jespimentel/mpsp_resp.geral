# mpsp_resp_geral
Webscraping do STJ para acompanhamento dos últimos REsp interpostos pelo MPSP no STJ.


O presente notebook buscou obter os resultados dos últimos recursos especiais interpostos pelo MPSP.

A análise foi feita a partir de dataset gerado pelo STJ no dia 17/06/2022, filtrando-se 1000 processos que tinham o MPSP como parte ou interessado, em ordem decrescente de autuação. 

O codigo foi escrito em Python. Foram utilizadas as bibliotecas pandas (para as operações com o dataframe), requests (para as requisições http ao site do STJ) e beautifulsoup (para a extração dos dados dos documentos html recuperados).
