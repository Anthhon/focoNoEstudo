---
title: "Moda Mediana Media Frequencia"
date: 2023-05-21T23:18:59-03:00
tags: ['Matemática']
---

![Capa](https://static.preparaenem.com/2023/01/oculos-e-xicara-de-cafe-proximos-a-um-caderno-com-um-grafico-indicando-desvio-padrao.jpg)

# Visão geral

Nesse post serão abordados conceitos básicos de **estatística** como **média, média ponderada, mediana, moda, e frequência.** 
Apesar de simples, são conceitos que valem a pena de serem revisados e costumam ser cobrados com certa frequência. No geral, 
esses conceitos são utilizados para melhor compreensão de certos conjuntos de dados.

# Média

Entre todas as medidas a média é a mais utilizada. Existem vários tipos de médias, porém, **as mais utilizadas são a média aritmética 
simples e a média aritmética ponderada.** 

# Média aritmética simples

Esse modelo acaba por ser o mais simples de se calcular, pois, o valor da média é obtido apenas somando os elementos de um 
conjunto e dividindo o valor pela quantidade de elementos! 

Por exemplo, vamos supor que você queira calcular a idade média 
dos funcionários de uma empresa. Considere o conjunto como uma lista com a idade de todos os funcionários **{28, 30, 37, 19, 21, 27, 33}** 
sabendo que a lista possui 7 funcionários resolveriamos da seguinte forma:

```
X = ( 28 + 30 + 37 + 19 + 21 + 27 + 33 ) / 7
X = 195 / 7
X = 27
```

Portanto, a idade média de um funcionário nessa empresa seria de 27 anos.

# Média aritmética ponderada

Na média aritmética ponderada temos alguns fatores extras que vão influenciar o cálculo, **cada valor dentro de um conjunto terá 
um "peso"** que vai ditar o quanto o valor vai influenciar a média final. Para calcular a média aritmética ponderada usaremos 
uma fórmula semelhante a seguinte:

```
X = p¹ * x¹ + p² * x² + p³ * x³ + ... pⁱ * xⁱ / p¹ + p² + p³
```

- X = Média ponderada
- p = Peso
- x = Valor

É um pouco confuso, mas talvez fique mais claro após um exemplo prático de como usar isso. Vamos tentar resolver a seguinte questão:

Em uma prova de matemática, um aluno tem que realizar duas atividades: um teste escrito, que tem **peso 3,** e um trabalho em grupo, 
que tem **peso 2.** As notas obtidas pelo aluno nessas atividades foram as seguintes: **8,0 no teste escrito e 9,5 no trabalho** em 
grupo. Qual a média aritmética ponderada das notas do aluno considerando o peso das atividades?

```
X = ( 3 * 8,0 + 2 * 9,5 ) / ( 2 + 3 )
X = ( 24 + 19 ) / ( 2 + 3 )
X = 43 / 5
X = 8,6
```

Aplicada a fórmula, é possível chegar no valor de 8,6 pontos para a média ponderada da nota do aluno.

# Exercícios

**Não pule os exercícios,** pois cada problema resolvido é um passo em direção ao seu crescimento e ao domínio da matéria. 
Seja persistente, dedique-se e descubra o poder que cada exercício tem em ensinar!

- Uma prova de matemática tem peso 3 e uma prova de história tem peso 2. Se um aluno obteve nota 8 na prova de matemática e nota 
7 na prova de história, qual é a sua média ponderada?
- Uma empresa vendeu 100 unidades de um produto no primeiro mês, 150 unidades no segundo mês e 200 unidades no terceiro mês. 
Qual é a média simples de vendas mensais?
- Uma pessoa investiu R$ 5.000,00 a uma taxa de juros de 4% ao ano e R$ 8.000,00 a uma taxa de juros de 6% ao ano. Qual é a taxa 
média de juros considerando o valor total investido?
