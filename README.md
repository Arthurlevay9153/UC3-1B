# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 

# Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

## String
É um dado que armazena um número, texto ou símbolo
ex: 
const a = 5
const b = 10

const calcular = (a*b) + (a*b)

console.log(`o resultado é ${calcular}`)

esse código mostra duas strings, o "a" e o "b", cada string tem um valor, e o console vai chamar uma outra string(calcular).
O resultado é que vai mostarr um texto onde vai mostar o resustaldo da variável calcular.

## Operador de comparação
operador de comparação compara seus operandos e retorna um valor lógico baseado em se a comparação é verdadeira. Os operandos podem ser numéricos, strings, lógicos ou objetos.
ex:
"==" (é igual a...)
"!=" (não é igual a...)
">" (maior que...)
"<" (menor que...)
">=" (maior o igual a...)
"<=" (menor ou igual a...)

## If e else & switch e case
Como o próprio nome diz, é um código que traz a a ideia de condição.

const name = prompt("Qual é o seu nome?")

  if (name == " Gustavo") {
    console.log(`Welcome ${name}`)
  } else {
    console.log(`Não sabia que teu nome era esse ${name}, for mal kkkk`)
  }

Esse código fala que se o "name" for "Gustavo", então o console.log vai dizer "Welcome Gustavo",
caso seja outro nome então o console vai mostar "Não sabia que teu nome era esse Gustavo, for mal kkkk".

Támbem temos o switch e case, que trazem a mesma ideia do "if e else", mas com diferenças de código, veja:
 const mês = prompt("Escreva um mês do ano para sber algum feriado desse mês");

 switch(mês){
    case "janeiro" || "Janeiro":
    alert("1 de janeiro: Dia mundial da paz")
    break;

## Array
É usado para declarar e organizar variaveis pelos seus valores, algo idêntico a escrever uma lista e chamar algum elemento da lista.
ex:
//const arr = ["sport", "naútico", "santa cruz"];
//console.log(arr[0]); 
//console.log(arr[1]); 
//console.log(arr[arr.length - 1]); <- 3-1 = 2


o primeiro console vai mostar o primeiro elemento(começando do 0 pra frente), que é o "sport".
o segundo console vai mostrar o segundo elemento(1), que é o "naútico"
já o terceiro vai mostar o o terceiro elemento, que é o santa cruz, já que ele está pegando todos os elementos que está na array(que saõ 3 elementos) e diminui -1, o que vai retornar o terceiro elemento(2).

### Atividades desenvolvidas
https://codepen.io/Arthur-Levay/pen/OJKXexW
https://codepen.io/Arthur-Levay/pen/KKjvmRz

