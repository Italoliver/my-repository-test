
Bem-vindo ao meu guia prático de JavaScript! Este documento serve como uma referência rápida para os principais conceitos e sintaxes da linguagem.

---

## 1. Variáveis e Tipos de Dados 📦

---

No JavaScript moderno, usamos principalmente `let` e `const`.

* **let**: Para valores que podem mudar.
* **const**: Para valores constantes (não podem ser reatribuídos).

```javascript
const nome = "Ítalo"; // String
let idade = 25;      // Number
const booleano = true; // Boolean (true/false)
let lista = [1, 2, 3]; // Array
let objeto = { cor: "azul", motor: 2.0 }; // Object
```
---

##2. Operadores Matemáticos ➕

---

let soma = 10 + 5;        // 15
let subtracao = 10 - 5;   // 5
let multiplicacao = 10 * 5; // 50
let divisao = 10 / 2;     // 5
let resto = 10 % 3;       // 1 (sobra da divisão)

---

##3. Estruturas Condicionais 🚦

---

Usadas para tomar decisões no código.
let hora = 14;

if (hora < 12) {
    console.log("Bom dia! ☀️");
} else if (hora < 18) {
    console.log("Boa tarde! 🌤️");
} else {
    console.log("Boa noite! 🌙");
}

---

##4. Estruturas de Repetição (Loops) 🔄

---

Para executar o mesmo código várias vezes.
// For: Sabendo o limite
for (let i = 0; i < 5; i++) {
    console.log("Repetição nº: " + i);
}

// While: Enquanto a condição for real
let contador = 0;
while (contador < 3) {
    console.log("Contando...");
    contador++;
}

---

##5. Funções ⚙️

---

Blocos de código que executam tarefas específicas.
// Função clássica
function saudar(nome) {
    return "Olá, " + nome + "! 😊";
}

// Arrow Function (Moderna)
const somar = (a, b) => a + b;

console.log(saudar("Ítalo"));
console.log(somar(10, 20));

---

##6. Manipulação de Arrays (Listas) 📋

---

Os métodos mais usados no dia a dia:
let frutas = ["Maçã", "Banana"];

frutas.push("Laranja"); // Adiciona ao fim
frutas.pop();           // Remove o último
frutas.forEach(f => console.log(f)); // Percorre a lista

---

##7. Manipulação do DOM (Web) 🌐

---

Como o JavaScript interage com o HTML:
// Selecionar um elemento
const botao = document.querySelector("#meuBotao");

// Adicionar um evento de clique
botao.addEventListener("click", () => {
    alert("Você clicou no botão! 🎉");
});

---

###Documento criado por Italoliver ⚡
