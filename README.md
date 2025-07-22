# Sistema Bancário em Java

Projeto final do curso **"Java: Criando a sua primeira aplicação"** da [Alura](https://www.alura.com.br).  
Uma aplicação de console que simula operações bancárias: cadastro de cliente, depósitos, transferências e consulta de saldo.  
Voltada para reforçar conceitos de programação em Java e boas práticas no uso de `Scanner` e estruturas de controle.

---

## Funcionalidades

- Cadastro inicial de cliente (nome, tipo de conta e saldo);
- Menu interativo com as opções:
  - **Consultar saldo**
  - **Receber valor (depósito)**
  - **Transferir valor** (com validação de saldo)
  - **Sair do sistema**
- Atualização dinâmica do saldo conforme operações;
- Entrada de dados via `Scanner`;
- Estrutura organizada utilizando `switch-case` e laços de repetição.

---

## Tecnologias utilizadas

- **Java 17+**
- IDE de sua preferência (IntelliJ, Eclipse, VS Code, etc.)

---

## Como executar

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```
2. Abra o projeto na sua IDE ou compile via terminal:
    ```bash
    javac AulaQuatroExUm.java
    ```
3. Execute:
    ```bash
    java AulaQuatroExUm
    ```

---

## Demonstração

Ao iniciar, o programa solicitará:
- Nome do cliente;
- Tipo da conta;
- Saldo inicial.

Em seguida, exibirá o menu de operações, permitindo realizar depósitos, transferências e consultar o saldo.

---

## Aprendizados

Este projeto reforçou os seguintes conceitos:
- Tipos de variáveis em Java;
- Leitura de dados com `Scanner` e tratamento de entradas;
- Estruturas de decisão, utilizando tanto `switch-case` quanto condicionais `if`;
- Laços de repetição (`while`);
- Formatação de strings com `String.format`.

---

## Próximos passos

- Adicionar autenticação simples (login/senha);
- Implementar histórico de transações;
- Melhorar validações de entrada (evitar valores inválidos).

