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
