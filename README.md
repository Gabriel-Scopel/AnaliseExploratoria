# AnaliseExploratoria
Projeto desenvolvido durante o curso paanalytics python para análise de dados

O objetivo principal do projeto é realizar um EAD (Análise Exploratória de Dados) do dataset fornecido e para tanto analisaremos as seguintes etapas:

1. Tipos de variáveis: 
    -Quantitativas: possuem um valor numérico associado
        -Discritivas: representam um conjunto finito
        -Contínuas: representam um conjunto infinit
    -Qualitativas: representam uma qualidade ou atributo
        -Ordinais: Apresentam ordem definida, ex: meses do ano
        -Nominais: Não apresentam ordem, ex: sexo, cor dos olhos, etc
    Para variáveis quantitativas, usamos estatísticas descritivas, como: moda, média, máximo, etc
    Para variáveis qualitativas, usamos tabelas de frequência

2. Detecção de dados nulos:
    Se faz necessário detectar e tratar dados nulos, pois a maioria de algoritmos de machine learning não trabalha com dados nulos
    Uma vez que esses dados nulos são detectados, podemos:
        -DropNa: exclusão dos dados nulos
        -FillNa: preencher esses dados

3. Detecção de Outliers:
    Um outlier é um valor que foge da normalidade e que pode causar anomalias nos resultados
    Métodos de detecção de um outlier:
        -Visualmente através de um boxplot
        -Calculando os limites superior e inferior da amostra e comparando com o ponto testado

4. Exploração Visual dos dados:
    Construção gráfica
