---
layout: essay
type: essay
title: 'Binary and Decimal'
# All dates must be YYYY-MM-DD format!
date: 2023-04-08
published: true
labels:
  - Math
  - Binary
---

pt-BR

[Números - Binário e Decimal]

Hoje quero falar um pouco sobre um assunto que as vezes assusta algumas pessoas, mas que podemos entender bem facilmente relacionando com algo que conhecemos bem.

Os números decimais que usamos no dia a dia, levam esse nome por terem base 10. Logo, os números binários levam o nome pela base 2. Simples

Entendido isso, podemos usar o seguinte exemplo:
Vamos contando 1, 2, 3, 4, 5, 6, 7... quando chegamos em 8, 9... pra ir pra o número 10, se adiciona um dígito na casa da esquerda (dezenas) e 0 na casa da direita (unidades). Isso se repete infinitamente com todas as casas. Adicionamos 1 dígito na casa seguinte (lembre que é sempre à esquerda) e recomeça a contagem.

Da mesma forma, no sistema binário temos 0, 1 e chegamos no limite. O que fazer? Adicionar 1 dígito à esquerda e 0 à direita (repetindo infinitamente também). Ficando da seguinte forma: 0 -> 1 -> 10 -> 11 -> 100 -> 101 -> 110 -> 111 -> 1000 -> 1001 -> 1010 -> e aqui já deu pra entender.

Ahh legal. Agora que sabemos como contar em números binários, como podemos transformar um número binário em decimal e um decimal em binário?

Após saber como contar, é interessante saber como converter um número em determinada base em outro. Aqui vamos falar de binário em decimal e vice-versa.

Digamos que eu tenha a resposta para tudo. Provavelmente você já sabe qual meu número, mas caso não, vamos converter ele de binário para decimal

A resposta para tudo em binário é 101010. Agora como saber em decimal?
Primeiramente sabemos que é um número de 6 dígitos.
Segundamente sabemos que é um número de base 2.

Então podemos fazer o seguinte cálculo:
1*2⁵ + 0*2⁴ + 1*2³ + 0*2² + 1*2¹ + 0*2⁰
Temos então o resultado:
32 + 0 + 8 + 0 + 2 + 0 = 42 <- essa é a resposta para tudo.

Acredito que você entendeu a lógica, mas caso não olhe novamente e veja o padrão.

Agora vamos supor que você já sabia que a resposta para tudo é 42 e queria saber em binário. Como fazer?

Novamente com um cálculo simples, mas dessa vez usando divisão.

42/2 = 21 (resta 0)
21/2 = 10 (resta 1)
10/2 = 5 (resta 0)
5/2 = 2 (resta 1)
2/2 = 1 (resta 0)
1/2 = 0 (resta 1)

Agora volte do último resto até o primeiro e compare com o número dito no meio do post. 😉

E é isto. Até logo!

en-US

[Numbers - Binary and Decimal]

Today, I want to talk a little about a topic that sometimes scares some people, but we can understand it quite easily by relating it to something we already know well.

The decimal numbers we use in our daily lives are called that because they are based on 10. Consequently, binary numbers are called so because they are based on 2. Simple.

With that understanding, we can use the following example:
We count 1, 2, 3, 4, 5, 6, 7... when we reach 8, 9... to get to the number 10, we add a digit on the left (tens) and 0 on the right (units). This process repeats infinitely with all the places. We add 1 digit in the next place (remember it's always to the left), and the counting starts again.

Similarly, in the binary system, we have 0, 1, and we reach the limit. What to do? Add 1 digit to the left and 0 to the right (also repeating infinitely). It looks like this: 0 -> 1 -> 10 -> 11 -> 100 -> 101 -> 110 -> 111 -> 1000 -> 1001 -> 1010 -> and by now, you've probably understood.

Ah, cool. Now that we know how to count in binary numbers, how can we convert a binary number to decimal and a decimal number to binary?

After learning how to count, it's interesting to know how to convert a number in one base to another. Here, we'll talk about binary to decimal and vice versa.

Let's say I have the answer to everything. You probably already know my number, but if not, let's convert it from binary to decimal.

The answer to everything in binary is 101010. Now, how do we find it in decimal?
First, we know it's a 6-digit number.
Second, we know it's a base 2 number.

So, we can do the following calculation:
12^5 + 02^4 + 12^3 + 02^2 + 12^1 + 02^0
Then we get the result:
32 + 0 + 8 + 0 + 2 + 0 = 42 <- that's the answer to everything.

I believe you've understood the logic, but if not, take another look and see the pattern.

Now, let's suppose you already knew that the answer to everything is 42 and you wanted to know it in binary. How do you do it?

Again, with a simple calculation, but this time using division.

42/2 = 21 (remainder 0)
21/2 = 10 (remainder 1)
10/2 = 5 (remainder 0)
5/2 = 2 (remainder 1)
2/2 = 1 (remainder 0)
1/2 = 0 (remainder 1)

Now, go from the last remainder to the first and compare it with the number mentioned in the middle of the post. 😉

And that's it. Goodbye!
