# 📚 API Web Biblioteca (CRUD: Entidade Livro)

Este projeto é uma API Web desenvolvida utilizando **TypeScript**, **Node.js** com framework **Express.js** e **TypeORM** para persistência de dados. [cite_start]O objetivo é implementar as operações **CRUD** (Create, Read, Update, Delete) para a entidade `Livro`, seguindo a arquitetura em camadas Controller/Repository[cite: 4, 16].

A persistência de dados é feita através do **TypeORM** utilizando **SQLite**, o que garante facilidade de execução em qualquer ambiente, incluindo o Codespaces.

---

## 🎯 Requisitos e Arquitetura

O projeto foi construído seguindo os requisitos definidos:

* **Tecnologia:** TypeScript, Node.js, Express.js.
* **Persistência:** TypeORM com SQLite (o arquivo `database.sqlite` é gerado automaticamente).
* **Arquitetura:**
    * [cite_start]**Controller:** Responsável por receber requisições HTTP e aplicar a lógica de negócio básica (validações). [cite: 18, 19, 20]
    * [cite_start]**Repository (DAO):** Responsável pela comunicação direta com o banco de dados usando o TypeORM. [cite: 21, 22, 26]
    * **Entity:** Define o modelo de dados (`Livro`) mapeado para a tabela `livros`.

## ⚙️ Configuração e Instalação

### Pré-requisitos

* Node.js (versão 18+)
* npm (Node Package Manager)
* Git

### 1. Clonar o Repositório

```bash
git clone [https://docs.github.com/pt/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github](https://docs.github.com/pt/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github)
cd [NOME DA PASTA DO PROJETO]
