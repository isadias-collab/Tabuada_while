# 🔢 Painel de Tabuadas com `while`

## 📚 Exercício de Lógica de Programação

## 🎯 Sobre o Projeto

Este projeto consiste no desenvolvimento de uma página web interativa que gera automaticamente as **tabuadas do 1 ao 10** ao clicar em um botão.

Diferente da versão anterior com `for`, nesta atividade a lógica foi construída utilizando a **estrutura de repetição `while`**, reforçando o controle manual das variáveis de contagem.

---

## 🧠 Situação-Problema

Foi proposta a criação de uma ferramenta educacional capaz de gerar as tabuadas de multiplicação de forma automática e organizada.

O sistema deveria:

- Gerar as tabuadas do 1 ao 10
- Utilizar laços de repetição `while`
- Organizar os resultados em formato visual estruturado
- Inserir o conteúdo dinamicamente na página

---

## 🚀 Funcionalidades

✔️ Botão para gerar as tabuadas  
✔️ Estrutura de repetição `while`  
✔️ Controle manual das variáveis `i` e `j`  
✔️ Cálculo automático de 1x1 até 10x10  
✔️ Inserção dinâmica com `.innerHTML`  
✔️ Layout organizado em formato de **cards**  

---

## 🛠️ Tecnologias Utilizadas

- HTML5  
- CSS3  
- JavaScript  

---

## 🔎 Estrutura do Funcionamento

### 📌 HTML
- Um botão que executa a função `gerarTabuadas()`
- Uma `<div>` com `id="resultado"` onde as tabuadas são exibidas

### 📌 CSS
- Estilização centralizada
- Organização dos cards com:
  - `display: flex`
  - `flex-wrap: wrap`
  - `gap` para espaçamento
- Botão estilizado com efeito `hover`
- Cards com fundo escuro e cantos arredondados

### 📌 JavaScript

O sistema utiliza **dois laços `while` aninhados**:

- 🔹 O primeiro `while` controla a tabuada atual (1 até 10)
- 🔹 O segundo `while` realiza as multiplicações (1 até 10)
- 🔹 As variáveis `i` e `j` são incrementadas manualmente
- 🔹 Os resultados são armazenados em uma variável `string`
- 🔹 Ao final, o conteúdo é inserido na página com `.innerHTML`

---

## 📘 Conceitos Trabalhados

- Estrutura de repetição `while`
- Laços aninhados
- Controle manual de variáveis
- Manipulação do DOM
- Concatenação de strings
- Organização visual com CSS
- Lógica de programação

---

## 👩‍💻 Objetivo Educacional

Desenvolver o raciocínio lógico por meio da construção de estruturas de repetição utilizando `while`, reforçando o controle de fluxo e a manipulação dinâmica de conteúdo em JavaScript.
