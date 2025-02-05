# desafio4-logica-js-projeto_inicial
 Desafio 4 de logica de programção javascript!

1- Crie um programa que utilize o console.log para exibir uma mensagem de boas-vindas.

**Objetivo:** console.log ('Seja bem-vindo!');

2- Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o console.log para exibir a mensagem "Olá, [seu nome]!" no console do navegador.

**Objetivo:** let nome = ('Jinglebobs');
    console.log(`Olá, ${Jinglebobs}!`);

3- Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o alert para exibir a mensagem "Olá, [seu nome]!" 

**Objetivo:** let nome = ('Jinglebobs');
    alert(`Olá, ${Jinglebobs!}`);

4- Utilize o prompt e faça a seguinte pergunta: Qual a linguagem de programação que você mais gosta?. Em seguida, armazene a resposta em uma variável e mostre no console do navegador.

**Objetivo:** let linguagem = prompt('Qual a linguagem de programação que você mais gosta?');
console.log(linguagem);

5- Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console.

**Objetivo:** let valor1 = 37;
let valor2 = 8;
let resultado = valor1 + valor2; // soma dos valores

console.log (`A soma de ${valor1} + ${valor2} é igual a ${resultado}!`);

6- Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console.

**Objetivo:** let valor1 = 50;
let valor2 = 32;
let resultado = valor1 - valor2; // subtração de valores

console.log (`A diferença de ${valor1} - ${valor2} é igual a ${resultado}!`);
7- Peça ao usuário para inserir sua idade com prompt. Com base na idade inserida, utilize um if para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console.

**Objetivo:** let idade = prompt('Olá, qual é a sua idade?');

// convertendo idade para um número
idade = Number(idade);

if (idade >= 18){
    alert('Você é maior de idade, seja bem-vindo!');
} else {
    alert('Você é menor de idade, seja bem-vindo!');
}

8- Crie uma variável "numero" e peça um valor com prompt verifique se é positivo, negativo ou zero. Use if-else para imprimir a respectiva mensagem.

**Objetivo:** let numero = prompt('Digite aqui qualquer número');

numero = Number(numero);

if(numero > 0){
    alert('Esse número é positivo!');
}   else if (numero < 0){
    alert('Esse número é negativo');
} else{
    alert('Esse número é zero');
}

9- Use um loop while para imprimir os números de 1 a 10 no console.

**Objetivo:** let numero = 1;

while (numero <= 10){
    console.log(numero);
    numero = numero +1;
}

10- Crie uma variável "nota" e atribua um valor numérico a ela. Use if-else para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console.

**Objetivo:** let nota = 20;

if (nota >= 7){
    console.log('Aprovado');
} else{
    console.log('Reprovado');
}

11- Use o Math.random para gerar qualquer número aleatório e exiba esse número no console.

**Objetivo:** let numeroAleatorio = Math.random();
console.log(numeroAleatorio);

12- Use o Math.random para gerar um número inteiro entre 1 e 10 e exiba esse número no console.

**Objetivo:** let numeroAleatorio = Math.floor(Math.random() * 10) + 1;
console.log(numeroAleatorio);

13- Use o Math.random para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.

**Objetivo:** let numeroAleatorio = Math.floor(Math.random() * 1000) + 1;
console.log(numeroAleatorio);
