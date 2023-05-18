---
title: "Progressão Aritmética e Geométrica"
date: 2023-05-16T22:41:08-03:00
tags: ['Matemática']
---

![Progressões Matemáticas](https://ids.si.edu/ids/deliveryService?id=NMAH-AHB2009q09004&max=1000)

# O que é uma progressão matemática?

Primeiramente, precisamos saber que **existem dois tipos de progressões numéricas, as aritméticas e geométricas.** 
Cada uma delas possui características específicas que as fazem únicas, porém, ambas compartilham características 
em comum, e é isso que vamos tentar entender primeiro. 

Antes de tudo, vale dizer que uma **progressão numérica nada mais é que uma sequência numérica que contém algum 
tipo de padrão.** Exemplo... 

```
{2, 4, 8, 16, 32...}
```

para os observadores, é facil notar que a sequência evolui multiplicando o primeiro termo por dois e 
assim em diante. **Outro fator importante para a consideração de uma progressão numérica é a 
existência de uma razão** (que no geral chamamos de "R"), uma maneira simples de entender isso é 
a seguinte, levando em consideração a mesma sequência que apresentei acima e entendendo a forma na qual 
ela progride é possível dizer que a razão dessa progressão numérica é de 2, simples assim.

Portanto, através dessas 2 características é possível se identificar uma progressão matemática, seja ela 
aritmética ou geométrica. **Devido esse padrão previsível das progressões matemáticas é possível calcular 
qualquer termo dessa sequência atravês do uso de fórmulas.**

# Progressões Aritméticas

Sabendo da existência dos dois tipos de progressões (aritméticas e geométricas) e o que as caracteriza como sendo 
progressões matemáticas, fica bem mais simples de se entender as suas individualidades, na progressão aritmética 
**o próximo termo (o número que vem a seguir na sequência) é constituído pela soma da razão com o número anterior.** 

Por exemplo, na sequência...

```
{2, 4, 6, 8, 10...}
```

é implícito que a sequência está aumentando de 2 em 2, por isso, podemos dizer que a razão da sequência é 
**r = 2** e com isso também **é possível prever que o próximo termo dessa sequência é 12.**

# Termos de uma PA (Progressão Aritmética)

Em muitos casos você vai ser instruído a **encontrar um termo específico de uma PA,** que normalmente 
demoraria muito para ser escrita manualmente, e para isso é necessário o uso de uma fórmula simples 
que vai requerer apenas o primeiro termo da razão. Segue abaixo a fórmula que deve ser utilizada e 
o significado de cada uma das letras:

```
aⁿ = a¹ + (n - 1)r
```

- aⁿ: Termo específico da sequência ou o termo a ser encontrado
- a¹: Primeiro termo da sequência
- n: Posição do termo a ser encontrado (enésimo termo da sequência)
- r: Razão da sequência numérica

Vamos tentar desenvolver uma questão exemplo para entender melhor essa fórmula. Encontre o 25º termo 
de uma sequência aritmética onde **r = 3 e a¹ = 12**. Para isso, basta aplicar a fórmula substituindo 
os respectivos valores...

```
a²⁵ = 12 + (25 - 1) * 3
a²⁵ = 12 + 24 * 3
a²⁵ = 12 + 72
a²⁵ = 84
```

Resolvendo a fórmula temos que o vigésimo quinto termo da sequência é o número 84, simples não é?

# Termo geral da PA

O termo geral de uma PA é **uma maneira de simplificar a fórmula de um termo da PA.** A fim de 
encontrar o termo geral de uma PA, basta conhecer o primeiro termo e a razão da PA, após 
substituir ambos na fórmula basta fazer o cálculo normalmente, vamos exemplificar o cálculo 
usando os seguintes valores **a¹ = 25 e r = 6**

```
aⁿ = 25 + (n - 1) * 6
aⁿ = 25 + 6n - 6
aⁿ = 19 + 6n
```

Após resolver você obterá uma equação de primeiro grau que deverá ser uma versão simplificada da fórmula 
original, **esse resultado pode ser utilizado para encontrar qualquer termo dessa progressão.**

Por exemplo, caso você queira encontrar o 12º termo dessa progressão usando o termo geral, basta 
substituir o valor **N** na fórmula:

```
a¹² = 19 + 6 * 12
a¹² = 19 + 72
a¹² = 91
```

# Soma dos termos da PA

```
Sⁿ = (a¹ + aⁿ) * n / 2
```

- Sⁿ: Soma dos termos da sequência (resultado final)
- aⁿ: Último termo da sequência
- a¹: Primeiro termo da sequência
- n: Quantidade de termos existentes

A soma dos termos de uma PA é algo que pode ser cobrado em algumas avaliações ou vestibulares, 
portanto, iremos abordar o assunto rapidamente. Essa fórmula serve para **calcular a soma de todos 
os termos de uma PA até um termo 'n'.** Um exemplo simples de como essa fórmula pode ser útil é o 
seguinte...

Dado a seguinte sequência numérica de números ímpares de **r = 2** {1, 3, 5, 7... 99}, temos cerca 
de 50 termos na sequência, calcular isso tudo a mão seria uma dor de cabeça, sendo assim, 
tendo em mente que **n = 50, a¹ = 1 e aⁿ = 99** vamos utilizar a fórmula...

```
Sⁿ = (1 + 99) * 50 / 2
Sⁿ = 100 * 50 / 2
Sⁿ = 5000 / 2
Sⁿ = 2500
```

# Progressão Geométrica

Saindo um pouco da PA (progressão aritmética) vamos agora conhecer a PG (progressão geométrica), de 
modo geral a PG é basicamente igual a uma PA, com exceção que, **o próximo termo de uma PG é calculado 
multiplicando o termo anterior pela razão,** ao invés da soma como havia sido feito na PA. Vamos a 
alguns exemplos para facilitar o entendimento, no bloco abaixo estão listados vários exemplos de PG:

```
{ 2, 4, 8, 16, 32, 64, 128... }
{ 3, 6, 12, 24, 48, 96... }
{ 17, 34, 68, 136, 272, 544... }
```

Para os que ao menos leram todas as sequências de verdade, deve ter ficado óbvio que todas elas 
possuem um **r = 2** já que aumental exponencialmente de 2 em 2.

# Termo de uma PG

```
aⁿ = a¹ * qⁿ⁻¹
```

Vale atentar que **em uma PG a razão é representada pela letra 'q' em vez de 'r'.** Portanto, não estranhem 
em ver essa letra sendo utilizada nas fórmulas. Essa fórmula possui a mesma função que a fórmula de termo da 
PA, você pode utiliza-la para encontrar um termo n dentro de uma sequência de maneira rápida.

Tentaremos usar o mesmo exemplo de antes nessa fórmula, tendo que **r = 3 e a¹ = 12** vamos tentar 
encontrar o 9º termo da sequência.

```
aⁿ = 12 * 3⁹⁻¹
aⁿ = 12 * 3⁸
aⁿ = 12 * (3² * 3² * 3² * 3²)
aⁿ = 12 * (9 * 9 * 9 * 9)
aⁿ = 12 * 6561
aⁿ = 78732
```

Dessa forma, temos que o 9º termo da PG é 78732. 

# Termo geral da PG

Para calcular o termo geral da PG, basta substituir os valores do primeiro termo e da razão na 
fórmula, tendo novamente **r = 3 e a¹ = 12:**

```
aⁿ = a¹ * qⁿ⁻¹
aⁿ = 12 * 3ⁿ⁻¹
```

Como a fórmula da PG envolve exponenciação, normalmente **a sua única tarefa ao calcular 
o termo geral vai ser substituir os valores,** pois o valor **'n'** do expoente se manterá o mesmo.

# Soma dos termos de uma PG

Somar os termos de uma PG seria tão trabalhoso quanto somar os termos de uma PA. Então, para 
facilitar esse tipo de trabalho é utilizado a seguinte fórmula:

```
sⁿ = a¹ * qⁿ⁻¹/q - 1
```

Para encontrar a soma dos primeiros 10 termos da seguinte sequência **{ 2, 4, 8, 16, 32... },** 
é possível notar que os valores da sequência são **r = 2 e a¹ = 2:**


```
s¹⁰ = 2 * 2¹⁰⁻¹/2 - 1
s¹⁰ = 2 * 2¹⁰⁻¹
s¹⁰ = 2 * 2⁹
s¹⁰ = 2¹⁰
s¹⁰ = 1024
```

Tendo todas essas 4 fórmulas em mente e sabendo como calcular o termo geral de uma PA e de uma PG, 
é possível resolver grande parte das questões de progressão numérica de maneira rápida e fácil. 
Vale sempre lembrar que a teoria não é nada sem a prática! Portanto, vou deixar uma pequena 
lista de questões para você resolver por conta própria.

# Exercícios

- Determine o próximo termo da sequência aritmética: {10, 15, 20, 25, ...}
- Encontre o 15º termo da sequência aritmética em que o primeiro termo é 3 e a razão é 7.
- Calcule a soma dos primeiros 8 termos da sequência aritmética: {2, 6, 10, 14, ...}
- Encontre o próximo termo da sequência geométrica: {2, 6, 18, 54, ...}
- Calcule o 10º termo da sequência geométrica em que o primeiro termo é 5 e a razão é 3.
- Determine a soma dos primeiros 6 termos da sequência geométrica: {3, 9, 27, 81, ...}

Resolva essas questões utilizando as fórmulas e conceitos apresentados sobre progressões aritméticas e geométricas.
