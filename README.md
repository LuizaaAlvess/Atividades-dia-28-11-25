# Atividades-dia-28-11-25

const entrada = require('readline-sync');

let nota = entrada.questionInt("Digite sua nota: ");

let nota1 = entrada.questionInt("Digite sua outra nota: ");

let nota2 = entrada.questionInt("Digite sua outra nota: ");

let nota3 = entrada.questionInt("Digite sua outra nota: ");

let calculo =  (nota + nota1 + nota2 + nota3) / 4;

console.log("A sua média é: ", calculo);


const salario = 2000;
const adicional = 500;
const extras = 100;
const desconto = 200;

const calculo = (salario + adicional + (extras * 5) - desconto)

console.log(calculo)



const n1 = 5.0;
const n2 = 6.0;
const n3 = 7.0;
const n4 = 8.0;

const diferenca1 = (n1 * n2) - (n3 * n4);
console.log("Diferença: ", diferenca1);


const n5 = 5.0;
const n6 = 6.0;
const n7 = -7.0;
const n8 = 8.0;

const diferenca2 = (n5 * n6) - (n7 * n8);
console.log("Diferença do segundo exemplo:", diferenca2);

