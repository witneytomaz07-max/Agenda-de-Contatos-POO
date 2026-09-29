# 📖 Agenda de Contatos

Projeto desenvolvido para a disciplina de **Programação Orientada a Objetos (POO)**, com o objetivo de criar uma agenda de contatos em Java, evoluindo o sistema gradualmente a cada versão.

---

## 📌 Versão Atual

**v0.3.0**

Nesta versão, o sistema recebeu a funcionalidade de alteração de contatos.
Agora é possível cadastrar, listar, procurar, alterar e excluir contatos. Os dados continuam sendo armazenados utilizando listas dinâmicas (`ArrayList`).

Cada contato possui:
- **Nome**
- **Celular**
- **E-mail**

---

## ⚙️ Funcionalidades

O sistema possui um menu interativo com as seguintes opções:

| Opção | Funcionalidade |
| :---: | :--- |
| **1** | Adicionar contato |
| **2** | Listar contatos |
| **3** | Procurar contato |
| **4** | Alterar contato |
| **5** | Excluir contato |
| **6** | Sair |

### ➕ Adicionar contato
Permite cadastrar um novo contato informando **Nome**, **Celular** e **E-mail**. Os dados são adicionados às respectivas listas utilizando o método `add()`.

### 📋 Listar contatos
Exibe todos os contatos cadastrados. Caso não exista nenhum contato cadastrado, o sistema exibe uma mensagem informando que a lista está vazia.

### 🔎 Procurar contato
Permite pesquisar um contato pelo nome. A busca utiliza `equalsIgnoreCase()`, portanto não diferencia letras maiúsculas e minúsculas.

### ✏️ Alterar contato
Permite localizar um contato pelo nome e atualizar seus dados (**Novo nome**, **Novo celular** e **Novo e-mail**). Após localizar o índice do contato, os dados são atualizados através do método `set()`. Caso o contato não seja localizado, uma mensagem informativa é exibida.

### 🗑️ Excluir contato
Permite excluir um contato informando seu nome. Quando localizado, seus dados são removidos das listas dinâmicas utilizando o método `remove()`.

### 🚪 Sair
Encerra a execução do programa.

---

## 🛠️ Tecnologias Utilizadas

- **Java**
- **Eclipse IDE**
- **Scanner** (entrada de dados pelo console)
- **List** e **ArrayList**

---

## 🧩 Conceitos Utilizados

Nesta versão foram aplicados conceitos fundamentais de Java e estruturas de dados:

- Variáveis e Tipos de Dados
- Estruturas Condicionais (`if` / `else`)
- Estruturas de Repetição (`for` / `while`)
- Classe `Scanner`
- Coleções Dinâmicas (`List`, `ArrayList`)
- Métodos de Coleção: `add()`, `get()`, `set()`, `remove()`, `size()`

---

## 🔄 Evolução do Projeto

- **v0.0.0**: Implementação inicial; cadastro de apenas um único contato com variáveis String simples.
- **v0.1.0**: Suporte a múltiplos contatos utilizando arrays fixos com capacidade máxima de 5 elementos.
- **v0.2.0**: Substituição de arrays por `ArrayList`, removendo a restrição de capacidade fixa.
- **v0.3.0**: Adição da funcionalidade de alteração de contatos usando `set()`, atualização do menu e refatoração do fluxo do sistema.

---

## 🚧 Limitações da Versão 0.3.0

- Os dados são mantidos em memória apenas enquanto o programa está em execução.
- Não há persistência de dados em arquivos ou banco de dados.
- Toda a lógica do programa está centralizada na classe `Principal`.
- Ainda não foi criada uma classe específica para representar o objeto `Contato`.
- Informações (nome, celular e e-mail) são mantidas em listas separadas.
- Falta de validação avançada nas entradas informadas pelo usuário.

---

## 📚 Objetivo Acadêmico

Este projeto está sendo desenvolvido como atividade prática para a disciplina de **Programação Orientada a Objetos (POO)**. O código é atualizado gradualmente ao longo do semestre para acompanhar e consolidar os conceitos abordados em aula.

**Status:** 🚧 Em desenvolvimento  
**Versão:** 0.3.0
