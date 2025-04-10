# Rust na Marra

Repositório pessoal para estudo sério e contínuo de Rust, com foco em backend robusto e tipado.  
O objetivo é dominar a linguagem de forma progressiva, do zero até a construção de APIs e integrações reais com banco de dados, testes e segurança.

---

## 🚀 Estrutura

```
rust-journey
├── fase01_entrada_e_fundamentos/
├── fase02_fluxo_controle_e_match/
├── fase03_funcoes_modulos_e_ownership/
├── fase04_structs_enums_e_trait_basica/
├── fase05_generics_trait_e_lifetime/
├── fase06_result_opcao_e_tratamento_erros/
├── fase07_collections_e_iteradores/
├── fase08_teste_modularizacao_crates/
├── fase09_async_tokio_http_server/
├── fase10_api_rest_com_axum/
├── fase11_db_postgres_sqlx/
├── fase12_autenticacao_e_segurança/
├── fase13_docker_env_logger_tracing/
└── fase14_gui_web
```

---

## 📍 Roadmap por Fases

### 🧱 Fase 01 - Entrada e Fundamentos
- `let`, `mut`, tipos primitivos
- `println!`, macros básicas
- Sintaxe e compilação
- `cargo`, `rustc`, `Cargo.toml`
- 🧪 Exercício: programa que recebe 2 números e soma

### 🧭 Fase 02 - Fluxo, If, Loop, Match
- `if/else`
- `loop`, `while`, `for`
- `match` poderoso
- 🧪 Exercício: calculadora simples com match

### 🔍 Fase 03 - Funções, Módulos e Ownership
- Definição de funções
- Organização em arquivos/mod
- Conceito central: ownership, borrowing, references
- 🧪 Exercício: função que recebe string e conta caracteres

### 🧱 Fase 04 - Structs, Enums e Traits básicas
- Criando Structs (tipo `User`)
- Enums (`Option`, `Result`, enums próprias)
- Traits simples (`Display`, `Debug`)
- 🧪 Exercício: criar sistema de usuários com Enum de status

### 🧠 Fase 05 - Generics, Traits e Lifetimes
- Como declarar tipos genéricos
- Traits genéricas e polimorfismo
- Lifetimes explicados com exemplos
- 🧪 Exercício: função que compara duas strings e retorna a maior

### 💥 Fase 06 - Option, Result e Tratamento de Erros
- `Option<T>` e `Result<T, E>`
- `unwrap`, `expect`, `?`
- `match` com erro
- 🧪 Exercício: função que lê um arquivo `.txt` e trata erros

### 🔗 Fase 07 - Collections e Iteradores
- `Vec`, `HashMap`, `HashSet`
- Métodos de iteradores
- `filter`, `map`, `collect`
- 🧪 Exercício: filtrar usuários por idade e agrupar por cidade

### 🧪 Fase 08 - Testes, Modularização, Crates
- Escrevendo testes unitários
- Organização em múltiplos arquivos e módulos
- Usando crates externas (ex: `chrono`, `serde`)
- 🧪 Exercício: criar um módulo de data e hora testado

### ⚡ Fase 09 - Async com Tokio e HTTP server
- `async`, `await`
- Tokio runtime
- Criando servidor com `hyper` ou `axum`
- 🧪 Exercício: servidor que responde "Hello JSON"

### 🔧 Fase 10 - API REST com Axum
- Rotas, extração de parâmetros
- Query params e payload JSON
- Middleware simples
- 🧪 Exercício: CRUD básico de usuários em memória

### 🧬 Fase 11 - Banco de Dados com SQLx
- Conexão com PostgreSQL
- Queries assíncronas com `sqlx`
- Migrações com `sqlx-cli`
- 🧪 Exercício: CRUD completo com Postgres

### 🔐 Fase 12 - Autenticação e Segurança
- JWT, senhas com `argon2`
- Criação de middleware de autenticação
- Headers, tokens e segurança
- 🧪 Exercício: login seguro com sessões

### 📦 Fase 13 - Docker, ENV, Logging, Tracing
- `.env` com `dotenvy`
- `tracing` para logs e observabilidade
- `Dockerfile` para Rust + PostgreSQL
- 🧪 Exercício: containerizar a API da Fase 11

### 🎨 Fase 14 - GUI e Web Frontend (Cereja)
- Interface gráfica com `iced`
- WASM para front-end web
- Projeto extra: criar dashboard para alertas CTI
- 🧪 Exercício: app gráfico ou web que consome a API feita

---

## 📌 Como rodar os exercícios

```bash
cd fase01_entrada_e_fundamentos
cargo run
```

Para compilar em release:

```bash
cargo build --release
```

Para rodar testes:

```bash
cargo test
```

---

## ✍️ Autor

Este projeto é mantido por Guilherme — AppSec / Rust Learner / Fã de RPG & NES  
> “A curiosidade é o combustível da segurança e da programação.”
