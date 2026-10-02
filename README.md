# Atividade de Métodos - Bootcamp Java

Este repositório contém a resolução da lista prática sobre **Métodos em Java**, cobrindo criação de métodos simples, passagem de parâmetros, valores de retorno (`return`), leitura de dados com `Scanner` e o conceito de **Sobremesa / Sobrecarga de Métodos (Overloading)**.

---

## 📋 Enunciados das Atividades

### 1 — Método Simples (`void`)
* **O que faz:** Cria um método chamado `mostrarBoasVindas()` fora do escopo do `main` (porém dentro da mesma classe) que imprime `"Bem-vinda ao curso de Java!"`.

### 2 — Método com Parâmetro (`String`)
* **O que faz:** Cria um método `saudar(String nome)` em uma classe separada chamada `Utilidades`. 
* **Execução:** Exibe uma saudação personalizada e é chamado três vezes com nomes diferentes.

### 3 — Método com Retorno de Cálculo (`int`)
* **O que faz:** Cria o método `dobro(int numero)` que realiza uma operação matemática e **devolve** o resultado usando `return`. O valor é guardado em uma variável e exibido no `main`.

### 4 — Método com Múltiplos Parâmetros e Scanner (`double`)
* **O que faz:** Cria o método `calcularMedia(double n1, double n2)`. 
* **Regra:** Combina a leitura de duas notas do usuário via `Scanner` no `main` e formata o resultado da média com duas casas decimais usando `printf`.

### 5 — Método Lógico com Retorno Booleano (`boolean`)
* **O que faz:** Cria o método `ehMaiorDeIdade(int idade)` que avalia uma condição e retorna `true` ou `false`.
* **Uso:** O retorno é aplicado diretamente dentro da estrutura condicional (`if/else`) no `main`.

### 6 — Sobrecarga de Métodos: Soma (`Overloading`)
* **O que faz:** Cria três métodos com exatamente o mesmo nome (`somar`), mas diferenciados pelas suas assinaturas:
  * Um recebendo dois inteiros.
  * Um recebendo três inteiros.
  * Um recebendo dois decimais (`double`).
* **Comportamento:** O Java identifica automaticamente qual versão executar com base nos argumentos passados.

### 7 — Sobrecarga de Métodos: Saudação (`Overloading`)
* **O que faz:** Cria dois métodos chamados `saudacao`:
  * Um sem parâmetros (imprime `"Olá!"`).
  * Um com parâmetro `String` (imprime `"Olá, [nome]!"`).
