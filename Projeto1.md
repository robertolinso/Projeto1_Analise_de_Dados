#-- Projeto1_Analise_de_Dados

O Projeto1 mostra a relação de aprovação ou reprovação e seus respectivos e financiamentos em uma eleição. 
Análise feita em Regressão Logistica.

#-- ✔
Explicativo das funções:

Pandas -> pandas é uma biblioteca de software criada para a linguagem Python para manipulação e análise de dados. 
Em particular, oferece estruturas e operações para manipular  tabelas numéricas e séries temporais.

Matplotlib -> Matplotlib é uma biblioteca de software para criação de gráficos e visualizações de dados 
em geral, feita para e da linguagem de programação Python e sua extensão de matemática NumPy.

Numpy -> NumPy é uma biblioteca para a linguagem de programação Python, que suporta o processamento de grandes,
multi-dimensionais arranjos e matrizes, juntamente com uma grande coleção de funções matemáticas de
alto nível para operar sobre estas matrizes.

sklearn -> scikit-learn é uma biblioteca da linguagem Python desenvolvida especificamente para aplicação prática de
machine learning (aprendizado de máquia).

LogisticRegression -> A regressão logística é uma técnica estatística que tem como objetivo produzir,
a partir de um conjunto de observações, um modelo que permita a predição de valores tomados por uma 
variável categórica, frequentemente binária, a partir de uma série de variáveis explicativas contínuas
e/ou binárias.

Para a pesquisa há um banco de dados no formato .CSV com dados ao qual será processado os resultados
almejados.

Disponibilizado a IDE -> (Integrated Development Environment). Um ambiente de desenvolvimento integrado (IDE)
é um software para criar aplicações que combina ferramentas comuns de desenvolvedor em uma única interface de 
usuário gráfica (GUI).

Veja:
Arquivo executável - IDE.exe

regressao_logistica_.ipynb - Arquivo em linguagem Python 

Eleicao.csv - Banco de dados

#--- ✔
Passo a passo:

1º Execute IDE.exe (Selecione e clique no arquivo).

2º Com a IDE "aberta" ao lado esquerdo selecione o arquivo regressao_logistica_.ipynb

3º É apresentado as céluas de linha de código.

4º De cima para baixo, selecione a segunda celula (quadrante com as linhas de código).
e precione a figura seta  ► (Run)  na barra de ferramentas. Esta ação, irá executar as funções de da célula. 

Desta forma o projeto será apresentado quadro a quadro ou celula por celula.

#-- ✔
Na primeira celula, o comentário referente a Regressão Logística.
Obs. o caracter  #  hashtag ou cerquilha no inicio da linha, define que é uma linha de comentário.    

#-- ✔
Na segunda celula, há a importação de bibliotecas para a execução das funções necessárias.  

#-- ✔
Na terceira celula apresenta o conteúdo da base de dados, Nome do candidato, Situação (1 eleito / 0 não eleito)
e Despesas da campanha. 

#-- ✔
Na quarta célula, será apresentado um gráfico de disperção com despesas e situação (1 eleito ou 0 Não eleito),
donde no eixo horizontal mostra os investimentos dos candidatos.

Será mostrado no gráfico, uma linha de separação dos eleitos ou não referente ao investimento e
a estatistica mostrando a contagem (count) do total de participantes Zero (0) e Um (1) representando eleitos ou não eleitos.
Obs A linha é mostrada na execução da Oitava célula.

#-- ✔
Na quinta célula, visualizamos o coeficiente de correlação entre as "Despesas" e "Situação (Eleito 1 - Sim / 0 - Não"
para ver se existe uma relação e se essa relação é positiva e a força da corelação entre ambas.
Podemos verificar o resultado na sua força de direção, se elá é Forte, Moderada ou Fraca.
Mais detalhes neste assunto ref. ao tema Regressão linear  - Correlação.

#-- ✔
Na sexta celula é demostrado um tratamento de dados, separação de variaveis dependente da indepentente
Transformação de X para o formato de matriz adicionando um novo eixo (newaxis)

#-- ✔
Na sétima celula é criado o modelo de regressão logística

#-- ✔
Na oitava celula é criado um gráfico de dispersão demonstrando os candidatos eleitos ou não e a linha
de melhor ajuste para o modelo na regressão logistica. 

#-- ✔
Portanto, caso queiram ampliar este estudo para a previsão de uma outra situação.

Sejam bem-vindos. 

Até mais! 😉

   
