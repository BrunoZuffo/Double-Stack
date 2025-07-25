# 🧩 Pilha Dupla em C | Double Stack in C

> 🇧🇷 Versão em português abaixo | English version below 🇺🇸

---

## 🇧🇷 Descrição

Projeto acadêmico desenvolvido para treinar o uso de estruturas de dados em C, mais especificamente o uso de uma **pilha dupla** (duas pilhas em um único vetor).

O projeto foi construído de forma modular, com um arquivo `.h` contendo as definições da estrutura e das funções, e um `main.c` com a implementação dos testes. Os comandos são executados pelo `main`, não via terminal.

### 📦 Funcionalidades

- Inserção e remoção em duas pilhas distintas (A e B)
- Compartilhamento de espaço em vetor único (`int valores[TAMANHO]`)
- Prevenção de sobreposição entre pilhas
- Controle de topo independente (`topoA`, `topoB`)

### 💻 Linguagens e Tecnologias

- **C**
- Estruturas (`struct`)
- Vetores estáticos
- Arquivos `.h` para modularização

### 📁 Estrutura dos Arquivos

```
.
├── pilhaDupla.h     # Definição da struct e das funções da pilha
├── main.c           # Execução dos testes e uso das funções
```

---

## 🇺🇸 Description

Academic project developed to practice data structures in C, specifically using a **double stack** (two stacks in a single array).

The project is modular, with a `.h` file for the structure and function declarations, and a `main.c` file for testing. Commands are executed through `main.c`, not the terminal.

### 📦 Features

- Push and pop operations for two separate stacks (A and B)
- Shared space using a single integer array (`int valores[TAMANHO]`)
- Prevents overlap between stacks
- Independent top control (`topoA`, `topoB`)

### 💻 Languages and Technologies

- **C**
- Structs
- Static arrays
- Header files for modularity

### 📁 File Structure

```
.
├── pilhaDupla.h     # Stack struct and function definitions
├── main.c           # Main file to execute test cases
```

---

👨‍💻 Developed by [@BrunoZuffo](https://github.com/BrunoZuffo)
