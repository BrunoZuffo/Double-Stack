# 🥞 Double Stack

Este repositório contém a implementação de uma **pilha dupla (double stack)** em linguagem C. A ideia principal é gerenciar **duas pilhas independentes (A e B)** utilizando **um único vetor compartilhado**, otimizando o uso de memória.

O projeto foi desenvolvido como exercício prático da disciplina de Estrutura de Dados na universidade.

---

## 📁 Estrutura do Projeto

- `main.c`: Função principal com testes das operações nas pilhas A e B.
- `pilhadupla.c`: Implementação das funções de manipulação da pilha dupla.
- `pilhadupla.h`: Arquivo de cabeçalho com a definição da struct e das funções.

---

## 🧠 Conceito: Pilha Dupla

A pilha dupla utiliza um único vetor (`valores[TAMANHO]`) para armazenar elementos de duas pilhas:

- A pilha **A** cresce do início para o fim do vetor.
- A pilha **B** cresce do fim para o início do vetor.

Isso permite que o espaço seja utilizado de forma mais eficiente, desde que as pilhas não colidam no meio.

---

## ⚙️ Funcionalidades

As principais operações disponíveis são:

- `pushA(pilha, valor)`: Insere um valor na pilha A.
- `pushB(pilha, valor)`: Insere um valor na pilha B.
- `popA(pilha)`: Remove o elemento do topo da pilha A.
- `popB(pilha)`: Remove o elemento do topo da pilha B.
- `clearA(pilha)`: Remove todos os elementos da pilha A.
- `clearB(pilha)`: Remove todos os elementos da pilha B.
- `imprimirA(pilha)`: Imprime os elementos da pilha A.
- `imprimirB(pilha)`: Imprime os elementos da pilha B.

---

## 🧪 Exemplo de uso

O `main.c` já contém uma sequência de comandos que demonstram a utilização das funções.

> ⚠️ **Importante**: Este código **não é interativo via terminal**.  
> As operações são **pré-definidas em `main.c`**, sendo executadas automaticamente ao rodar o programa.

```c
Pilha* pilha = criarPilha();

pushA(pilha, 18);
pushA(pilha, 30);
imprimirA(pilha);  // [|30|18|]

pushB(pilha, 9);
pushB(pilha, 23);
imprimirB(pilha);  // [|23|9|]

clearA(pilha);
clearB(pilha);
```

---

## 🛠️ Compilação e Execução

### ✔️ Requisitos

- Compilador C (como `gcc`)
- Code::Blocks (opcional, utilizado no desenvolvimento)

### 🔧 Compilando via terminal

```bash
gcc main.c pilhadupla.c -o double_stack
./double_stack
```

---

## 👨‍💻 Autor

Este projeto foi desenvolvido como exercício prático na universidade por:

**Bruno Zuffo**  
Estudante de Engenharia de Computação  
[LinkedIn]([https://linkedin.com/in/seu-perfil](https://www.linkedin.com/in/bruno-zuffo-10088b216/?trk=opento_sprofile_details))

---

## 📜 Licença

Este projeto é de uso educacional. Sinta-se livre para estudar, modificar e reutilizar com fins acadêmicos.
