# Atividade de Programação Back-End

## Objetivo

Nesta atividade vamos praticar conceitos básicos de JavaScript e Programação Back-End, trabalhando com listas de objetos e organização de dados.

Antes da atividade, será mostrado um exemplo utilizando uma lista de jogos de videogame.

---

## Exemplo: Lista de Jogos

No exemplo, criamos um arquivo chamado:

```text
jogos.js
```

Cada jogo possui as seguintes informações:

- id
- nome
- plataforma
- gênero
- ano
- preço

### Exemplo de código

```javascript
const jogos = [
    {
        id: 1,
        nome: "EA Sports FC 26",
        plataforma: "PS4",
        genero: "Esporte",
        ano: 2025,
        preco: 299.90
    },
    {
        id: 2,
        nome: "Minecraft",
        plataforma: "Multiplataforma",
        genero: "Aventura",
        ano: 2011,
        preco: 99.90
    },
    {
        id: 3,
        nome: "GTA V",
        plataforma: "PS4",
        genero: "Ação",
        ano: 2013,
        preco: 149.90
    }
];

console.log(jogos);
```

### Explicação

A variável `jogos` contém uma lista de objetos.

Cada objeto representa um jogo e possui suas próprias informações.

O comando abaixo exibe todos os jogos no console:

```javascript
console.log(jogos);
```

---

# Atividade

Crie um programa chamado:

```text
produtos.js
```

O programa deverá conter uma lista de produtos com as seguintes informações:

- nome
- categoria
- quantidade
- preço
- fornecedor

O programa deve exibir a lista de produtos e suas informações no console.

---

## Exemplo da estrutura

```javascript
const produtos = [
    {
        nome: "Teclado",
        categoria: "Informática",
        quantidade: 10,
        preco: 120.00,
        fornecedor: "TechStore"
    }
];

console.log(produtos);
```

---

## Desafio

Adicione pelo menos **5 produtos diferentes** na lista.

Depois execute o programa no terminal com:

```bash
node produtos.js
```

O resultado deverá mostrar todos os produtos cadastrados.

---

## Conceitos trabalhados

- JavaScript
- Variáveis
- Arrays
- Objetos
- Listas
- `console.log()`
- Node.js

---

## Resumo

No final de atividade leve para os professores, Davi e Samuel e mostre q esta funcionado o POST, PUT, PATCH, DELETE e GET dentro do Thunder Client
