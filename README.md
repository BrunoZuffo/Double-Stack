# 🧩 Double Stack in C

## Description

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
├── pilhaDupla.h     # Stack struct and function definitions
├── main.c           # Main file to execute test cases
```

---

👨‍💻 Developed by [@BrunoZuffo](https://github.com/BrunoZuffo)
