# Repositório Projeto Colaboração DIO

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status: Em Desenvolvimento](https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue.svg)](#)

Documentação oficial do repositório prático desenvolvido para consolidar os aprendizados adquiridos nos módulos iniciais da **Formação GitHub** oferecida pela **DIO (Digital Innovation One)**.

---

## 🎯 Objetivo do Projeto

Este repositório tem como finalidade principal comprovar a assimilação teórica e o domínio prático dos conceitos abordados nos três primeiros blocos de conhecimento da formação:

1. **Introdução ao Git e Controle de Versão** — Compreensão da arquitetura do Git, ciclo de vida dos arquivos e comandos fundamentais.
2. **Navegação e Gestão via Terminal (CLI)** — Utilização fluida da linha de comando para manipular arquivos, diretórios e repositórios locais.
3. **Colaboração e Recursos Avançados do GitHub** — Domínio de recursos remotos, navegação, uso do editor online (`github.dev`), gerenciamento de branches, commits e colaboração na nuvem.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- **Git:** Controle de versão distribuído.
- **GitHub & GitHub.dev:** Hospedagem de código, controle de versão remoto e edição online via navegador.
- **HTML5 & CSS3:** Estruturação e estilização de página web responsiva criada durante as atividades práticas.
- **Markdown:** Elaboração e estruturação desta documentação técnica.

---

---

# 📋 Passo a Passo de Execução do Projeto


---

# 🏁 Etapa 1 — Planejamento e Configuração Inicial

Nesta etapa foi preparada a estrutura inicial do projeto e configurado o ambiente de colaboração entre as duas contas do GitHub.

- [x] **Criação do Repositório Remoto**
  - Inicialização do repositório **Git-Github-Colaboracao** na conta principal (*Proprietária*).

- [x] **Desenvolvimento da Aplicação Base**
  - Criação do arquivo `index.html`, implementando um layout responsivo em três colunas, contendo imagens laterais e a *Litany of Sacrifice* na região central.

- [x] **Documentação Inicial**
  - Criação e estruturação do arquivo `README.md`, utilizado como documentação técnica do projeto.

- [x] **Configuração da Colaboração**
  - Envio do convite para a conta secundária através de **Settings → Collaborators**.

- [x] **Aceite do Convite**
  - Confirmação da permissão de escrita (*Write Access*) pela conta colaboradora.

---

# 🔄 Etapa 2 — Sincronização Local e Organização dos Recursos

Nesta fase foi estabelecida a comunicação entre o repositório local e o remoto, além da organização da estrutura do projeto.

- [x] **Edição Remota com GitHub.dev**
  - Utilização do editor web baseado no VS Code (atalho `.`) para realizar alterações diretamente no repositório remoto.

- [x] **Configuração do Repositório Remoto (`origin`)**

```bash
git remote add origin https://github.com/EdsonFS3110/Git-Github-Colaboracao.git
```

- [x] **Primeira Sincronização do Projeto**

```bash
git pull origin main
```

- [x] **Organização dos Recursos Estáticos**
  - Criação do diretório `assets/`.
  - Inclusão das imagens utilizadas no projeto.
  - Atualização das referências no arquivo `index.html`.
  - Registro das alterações através de commit.

---

# 🌿 Etapa 3 — Fluxo de Branches e Colaboração

Nesta etapa foi aplicado o fluxo de desenvolvimento baseado em **Feature Branches** e **Pull Requests**.

## 🌱 Criação da Feature Branch

```bash
git checkout -b feature/adiciona-assets
```

- [x] Desenvolvimento isolado em uma branch dedicada, evitando alterações diretas na branch `main`.

---

## 🚀 Publicação da Branch Remota

```bash
git push -u origin feature/adiciona-assets
```

- [x] Envio da branch para o GitHub.
- [x] Configuração automática do *upstream*.

---

## 🔀 Pull Request

- [x] Criação do Pull Request.
- [x] Revisão das alterações.
- [x] Verificação da inexistência de conflitos.
- [x] Aprovação do Pull Request.
- [x] Merge da branch para a `main`.

---

## 🔄 Atualização da Branch Principal

```bash
git checkout main
git pull origin main
```

- [x] Sincronização da branch principal local após a conclusão do Merge.

---

## 📝 Gerenciamento de Tarefas

- [x] Criação de uma **GitHub Issue** para registrar melhorias futuras e acompanhar o ciclo de vida das demandas do projeto.

---

# 🎯 Competências Praticadas

Ao longo deste laboratório foram exercitados os seguintes conceitos:

- ✅ Criação de repositórios remotos
- ✅ Configuração de colaboração entre múltiplas contas
- ✅ Utilização do GitHub.dev
- ✅ Configuração do repositório remoto (`origin`)
- ✅ Sincronização entre repositórios local e remoto
- ✅ Organização da estrutura de arquivos
- ✅ Criação e gerenciamento de Feature Branches
- ✅ Publicação de branches remotas
- ✅ Fluxo de trabalho com Pull Requests
- ✅ Processo de revisão e Merge
- ✅ Gerenciamento de tarefas com GitHub Issues

---

# 💡 Objetivos de Aprendizagem

Este laboratório teve como objetivo consolidar a utilização prática do fluxo de trabalho colaborativo utilizando Git e GitHub, abordando desde a configuração inicial do repositório até o processo completo de colaboração entre desenvolvedores.

Ao final da atividade foram praticados:

- organização do histórico de desenvolvimento;
- trabalho colaborativo utilizando múltiplas contas;
- sincronização entre ambiente local e remoto;
- gerenciamento de branches;
- utilização de Pull Requests;
- revisão de código;
- gerenciamento de Issues;
- aplicação das boas práticas recomendadas para projetos hospedados no GitHub.

# 📚 Conceitos Estudados

| Conceito | Situação Prática |
|----------|------------------|
| Repository | Criação do repositório remoto |
| Clone | Obtenção da cópia local |
| Remote | Configuração do `origin` |
| Commit | Registro das alterações |
| Push | Envio das alterações |
| Pull | Sincronização do repositório |
| Branch | Desenvolvimento isolado |
| Pull Request | Revisão e integração |
| Merge | Consolidação das alterações |
| GitHub Issues | Gerenciamento de tarefas |
| GitHub.dev | Edição remota |

## 🚀 Como Executar o Projeto Localmente

1. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
