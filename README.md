# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
### String: É uma sequência de caracteres alfanuméricos (letras, números e/ou símbolos).
### Variaveis: São usadas para armazenar e manipular dados.
### number: Usado para definir números, feito (R$)
```js
const fruta = banana
console.log(nome)
```


## Atividades desenvolvidas
### Aprender a vender algo com uso de JS
```js
const nome = Miguel
console.log(nome)
```
```js
const livros = [
    "Pelé",
    "A divina comédia",
    "Hamlet",
    "Dom Quixote",
    "Fausto",
    "Orgulho e preconceito",
    "Frankenstein",
    "Os três mosqueteiros",
    "O corvo",
    "Moby Dick",
    "Madame Bovary",
    "As flores do mal",
    "Os miseráveis",
    "O médico e o monstro",
    "O retrato de Dorian Gray",
    "Em busca do tempo perdido",
    "Ulisses",
    "Mrs. Dalloway",
    "Admirável mundo novo",
    "1984",
    "Steven Gerrard - O Milagre de Istanbul",
    "France Football - Ballon d'or"
];

// Remover o primeiro e o último livro do array respctivamente
livros.shift(); 
livros.pop();  
// Função para verificar se o livro está disponível
function verificarDisponibilidade(livro) {
    if (livros.includes(livro)) {
        console.log(`O livro "${livro}" está disponível na livraria.`);
    } else {
        console.log(`O livro "${livro}" não está disponível na livraria.`);
    }
}

// Prompt para o usuário inserir o nome do livro que deseja
const livroProcurado = prompt("Digite o nome do livro que você está procurando:");
verificarDisponibilidade(livroProcurado);
```
## Switch Case:
### Switch é um tipo de mecanismo de controle de seleção usado para permitir que o valor de uma variável ou expressão altere o fluxo de controle da execução do programa por meio de pesquisa e mapa.
Exemplo:
```js
function mostrarMensagem(Feriados) {
  switch (Feriados.toLowerCase()) {
    case "janeiro":
      alert("Dia 1: Dia Mundial da Paz");
      break;
    case "fevereiro":
      alert("Fevereiro só tem feriado quando o carnaval cai neste mês");
      break;
    case "março":
      alert("Última Sexta-Feira do Mês: Sexta-Feira Santa");
      break;
    case "abril":
      alert("Dia 21: Tiradentes");
      break;
    case "maio":
      alert("Dia 1: Dia do Trabalhador Dia 30: Corpus Christi");
      break;
    case "junho":
      alert("Não há feriados nacionais em Junho!");
      break;
    case "julho":
      alert("Não há feriados nacionais em Julho!");
      break;
    case "agosto":
      alert("Não há feriados nacionais em Agosto!");
      break;
    case "setembro":
      alert("Dia 7: Independência do Brasil");
      break;
    case "outubro":
      alert("Dia 12: Nossa Senhora de Aparecida Padroeira do Brasil");
      break;
    case "novembro":
      alert("Dia 2: Finados, Dia 15: Proclamação da República");
      break;
    case "dezembro":
      alert("Dia 25: Natal");
      break;
    default:
      alert("Esse mês não existe! :/");
  }
}

let Feriados = prompt(
  "De qual mês você deseja saber os feriados? (Janeiro, Fevereiro, Março, Abril, Maio, Junho, Julho, Agosto, Setembro, Outubro, Novembro e Dezembro)"
);
mostrarMensagem(Feriados);
```
## If e Else:
### A instrução if executa uma instrução se uma condição especificada for verdadeira. Se a condição for falsa, outra instrução na cláusula else opcional será executada.
exemplo:
```js
function soma (num1, num2) {
console.log(num1 + num2)
}
console.log(soma(7,2))

function soma (num1, num2) {
console.log(num1 - num2)
}
console.log(soma(7,2))

const compra1 = prompt("qual o valor da primeira compra?")
const compra2 = prompt("qual o valor da segunda compra?")

if(compra1 > compra2) {
console.log(soma(compra1, compra2))
}else if (compra1 < compra2) {
console.log(subtracao(compra1, compra2))
} else {
console.log("Erro")
}
```
## Projeto de um jogo em JS
Exemplo:
```js
function mostrarMensagem(tipoDeLuta) {
  switch (tipoDeLuta.toLowerCase()) {
    case "muay thai":
      alert("Muay Thai é conhecido como a arte dos oito membros!");
      break;
    case "karatê":
      alert(
        "Karatê é uma arte marcial japonesa focada na velocidade e defesa!"
      );
      break;
    case "jiu-jitsu":
      alert(
        "Jiu-Jitsu é uma arte marcial que enfatiza o grappling e a defesa pessoal!"
      );
      break;
    case "taekwondo":
      alert(
        "Taekwondo é uma arte marcial coreana conhecida por seus chutes altos!"
      );
      break;
    case "boxe":
      alert("Boxe é um esporte de combate focado em socos e movimentação!");
      break;
    case "capoeira":
      alert(
        "Capoeira é uma expressão cultural afro-brasileira que combina dança, acrobacias e música!"
      );
      break;
    case "luta de rua":
      alert(
        "Luta de Rua é um estilo de combate sem regras específicas, focado na autodefesa!"
      );
      break;
    case "luta livre":
      alert(
        "Luta Livre é uma arte marcial brasileira que combina técnicas de grappling e submissão!"
      );
      break;
    default:
      alert("Tipo de luta não reconhecido. Tente novamente!");
  }
}

let tipoDeLuta = prompt(
  "De qual M^? (Muay Thai, Karatê, Jiu-Jitsu, Taekwondo, Boxe, Capoeira, Luta de Rua, Luta Livre)"
);
mostrarMensagem(tipoDeLuta);
```
