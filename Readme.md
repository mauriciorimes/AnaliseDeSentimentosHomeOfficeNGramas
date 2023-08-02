Uma análise de sentimentos para ensinar um algoritmo predizer se tweets que comentem sobre o Home Office, são a favor ou contra essa modalidade de trabalho. Foram usadas ferramentas e estratégias de machine learning, junto com Python e uso da biblioteca Pandas.

Tratando de uma análise supervisionada, onde cada aluno da sala, classificou 700 tweets, que numa sala com 12 alunos, totalizando em média 2800 tweets, já que a mesma tabela de 700 tweets era entregue para 3 alunos, para assim comparar os resultados da classificação.

Obs: um exemplo de tabela está contido no repositório

Nessa etapa, todos os tweets classificados foram reunidos em um único arquivo csv (disponível no repositório), onde foram feitos alguns testes, como demonstrar tabelas, e disposição dos tweets separados por sua classificação.

Tendo de resultado: 
NEUTRO      1454
POSITIVO    1032
NEGATIVO     336

Logo após os testes e leitura de alguns dados, foi removida a classe: "NEUTRO", que não é de interesse do algoritmo aprender se um tweet é neutro, e sim se é positivo ou negativo.

Foram removidos os tweets que pareciam duplicados, indo para o seguinte resultado.

POSITIVO    500
NEGATIVO    336

Depois foram removidos caracteres especiais, para deixar a análise mais precisa e focadas nas palavras.

Foram removidas as "stop words" e determinado o idioma para português.

Para assim gerar os resultados, que podem ser melhores mostrados em: https://colab.research.google.com/drive/1cP6sh9rDBb2eYctVOGtg4DV2h9ozimFB?usp=sharing




