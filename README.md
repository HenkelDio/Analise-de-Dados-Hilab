# Teste estágio análise de dados

Essa é a solução do teste aplicado para o estágio de análise de dados.

## Conteúdos

- [Review](#review)
  - [O Teste](#o-teste)
  - [Construído com](#construído-com)
- [Meu processo](#meu-processo)
- [Perguntas](#perguntas)
- [Autor](#autor)

# Review

## O teste

Dado um dataset quebrado em 3 partes iguais para que fossem unifidados e analisados, conforme perguntas.

## Construído com:

- Python
- Pandas 
- sqlite3
<br>
(Todas as bibliotecas e suas versões estão no requirements.txt)


# Meu processo

Foi mesclado os 3 arquivos em um .csv para análise posterior, e utilizado o separador "^", para evitar problemas de leituras do python. Não limitei as casas decimais do campo "prop", para previnir uma análise errada. 

# Perguntas

### <b>1- Quantos nomes diferentes existem por ano a partir de 2000? Forneça uma tabela e demonstre os resultados graficamente.</b>

![](/images/first.png)

### <b>2- Qual a média e a mediana da contagem de bebês no dataset. Qual dessas medidas de tendência central você escolheria para descrever esse dado, justifique sua opção.</b>

Média de contagem de bebês: <i><b>180.87</b></i>
<br>
Mediana de contagem de bebês:<i><b> 12</b></i>
<br>
Optaria por usar a mediana, pois os valores da contagem de bebês (n) é muito discrepante.

### <b>3- Qual a média e desvio padrão da contagem de bebês no ano de 1997?</b>
Média da contagem de bebês: <i><b>134.39</b></i>
<br>
Desvio padrão da contagem de bebês: <i><b>1024.32</b></i>

### <b>4- Levando em conta que o dataset engloba o nascimento de todos os bebês do país imaginário Hilablândia. Qual o total de nascimentos no ano de 2002? Desses, quantos são do sexo feminino e quantos do sexo masculino?</b>
Total de nascimentos em Hilablândia em 2002: <i><b>30563</b></i>
<br>
Total de nascimentos femininos: <i><b>18081</b></i>
<br>
Total de nascimento masculinos: <i><b>12482</b></i>

### <b>5- Descobri qual é nome mais utilizado por ano desde do ano 2000.</b>

![](/images/second.png)

Com esse dado, conseguimos concluir que o nome mais utilizado desde 2000, é Isabella.

# Autor

- Linkedin - [Willian Henkel](https://www.linkedin.com/in/willian-henkel-b652b3205/)