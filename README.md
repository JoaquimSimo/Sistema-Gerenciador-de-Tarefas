# 📝 Sistema Gerenciador de Tarefas (Task Manager API)

## 📌 Descrição do Projeto

Este projeto consiste em uma API simples para gerenciamento de tarefas, desenvolvida com foco na adoção de boas práticas de versionamento com Git.

O sistema permite realizar operações básicas de CRUD:

* Criar tarefas
* Listar tarefas
* Atualizar tarefas
* Deletar tarefas

O principal objetivo não é apenas a implementação funcional, mas sim simular um ambiente profissional de desenvolvimento com controle de versão estruturado.

---

## 🚀 Tecnologias Utilizadas

* Linguagem: (Python)
* Framework: (Flask)
* Git & GitHub
* REST API

---

## 🌿 Estratégia de Branches

O projeto segue o modelo de versionamento baseado em Git Flow:

* **main** → versão estável (produção)
* **develop** → integração de funcionalidades
* **feature/** → desenvolvimento de novas funcionalidades
* **hotfix/** → correções urgentes em produção

---

## 🔄 Fluxo de Desenvolvimento

1. Criar uma branch a partir de `develop`

   ```bash
   git checkout -b feature/nome-da-feature
   ```

2. Desenvolver a funcionalidade

3. Realizar commits organizados

4. Subir a branch:

   ```bash
   git push origin feature/nome-da-feature
   ```

5. Criar Pull Request para `develop`

6. Após validação, fazer merge

7. Quando pronto, realizar release para `main`

---

## 🧾 Padrão de Commits

Os commits seguem o padrão semântico:

* `feat:` → nova funcionalidade
* `fix:` → correção de bug
* `docs:` → documentação
* `refactor:` → melhoria de código
* `chore:` → tarefas auxiliares

### Exemplos:

```bash
feat: adiciona criação de tarefas
fix: corrige erro ao deletar tarefa
docs: atualiza README
refactor: melhora estrutura das rotas
```

## 📂 Estrutura do Projeto

```
📦 projeto
 ┣ 📂 src
 ┃ ┣ 📂 frontend
 ┃ ┗ 📂 backend
 ┣ 📄 .gitignore
 ┗ 📄 README.md
```

## 🐞 Correção de Bugs (Hotfix)

Fluxo adotado:

1. Criar branch `hotfix/descricao`
2. Corrigir problema
3. Merge direto para `main`
4. Sincronizar com `develop`

---

## 📄 Licença

Este projeto é acadêmico e de uso educacional.
