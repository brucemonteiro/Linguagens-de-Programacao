# LOTOFÁCIL em Java

Este é um projeto onde vamos criar uma lotofácil para que os usuários possam realizar apostas e consecutivamente receber prêmios por elas. Essa lotofácil será dividida em três etapas: apostas de 1 a 100, apostas de A à Z e apostas entre par ou ímpar.

### Regras para a aposta de 0 a 100:

- Utilizei a biblioteca `Scanner`, para que o programa leia se o número escolhido está entre 0 e 100, e caso não esteja, seja imprida a mensagem de aposta inválida.
- Utilizei a biblioteca `Random` para ser sorteado um número de 0 a 100.
- Feito isso, o programa vai comparar o número escolhido pelo apostador e o número do sistema.

### Regras para a aposta de A à Z:

- Utilizei o método `System.in.read()` para ler um caractere de A à Z , sendo ele maiúsculo ou minúsculo. Se não for uma letra, a aposta será inválida. Utilizei o método `Character.isLetter()` para ver se a entrada digitada é uma letra válida.
- A aposta do usuário será covertida para maiúscula pelo `Character.toUpperCase()`.
- Feito isso, o programa vai comparar a letra escolhida com a letra do sistema, que será a inicial do meu nome (B).


### Regras para a aposta de número par ou ímpar:

- Utilizei a biblioteca  `Scanner` para ler um número inteiro escolhido pelo apostador.
- Utilizei o operador de módulo (%) para verificar se o número é par ou ímpar.
- Se a divisão do número por 2 for 0, o número é par.

### REGRA LOTOFÁCIL:

O usuário poderá apostar quantas vezes ele quiser. Enquanto o usuário não digitar 0 para sair, novas apostas serão permitidas.



## Como rodar o projeto

1. Certifique-se de ter o JDK instalado em sua máquina.

2. Siga as instruções do código.

3. Vá até o diretório do projeto.

4. Compile o código-fonte.

5. Execute o programa.

6. Siga as instruções para fazer suas apostas na LOTOFÁCIL.


Este projeto foi desenvolvido utilizando a versão do JDK 21.
Bibliotecas usadas: Scanner,Random. Métodos usados: System.in.read(),Character.toUpperCase().

SUPORTE UTILIZADO NO TRABALHO: Chatgpt e Github/lucas-novaesm


# Rodando o projeto


![Imagem do WhatsApp de 2024-04-03 à(s) 14 00 58_3eab45a2](https://github.com/brucemonteiro/Linguagens-de-Programacao/assets/163943761/18c23914-780e-44ae-a30f-0ed7147d20de)

![Imagem do WhatsApp de 2024-04-03 à(s) 14 00 58_5f311795](https://github.com/brucemonteiro/Linguagens-de-Programacao/assets/163943761/4a3c1f35-3fe9-4864-a33f-b196044a33a4)

![Imagem do WhatsApp de 2024-04-03 à(s) 14 00 58_5f311795](https://github.com/brucemonteiro/Linguagens-de-Programacao/assets/163943761/747aaac6-0cce-4e7c-8365-25d73f4ab014)

![Imagem do WhatsApp de 2024-04-03 à(s) 14 00 58_5f311795](https://github.com/brucemonteiro/Linguagens-de-Programacao/assets/163943761/21cede9f-a719-43e9-926e-26dc37180f4c)












