# 🥦 Controle de Estoque Hortifruti

Sistema web para gerenciamento de estoque de frutas, verduras e legumes, com foco em controle de validade, perdas e organização de produtos.

---

## 📌 Objetivo

Este projeto tem como objetivo ajudar pequenos comércios (verdurões, hortifrutis, sacolões) a controlar seu estoque de forma simples, reduzindo desperdícios e melhorando a gestão de compras e vendas.

---

## 🚀 Funcionalidades (MVP)

* Cadastro de produtos
* Cadastro de fornecedores
* Registro de entrada de mercadorias
* Registro de saída (venda, perda, ajuste)
* Controle de estoque atual
* Alerta de estoque mínimo
* Controle de validade

---

## 🧩 Funcionalidades futuras

* Relatórios de vendas e perdas
* Ranking de produtos mais vendidos
* Controle de usuários
* Leitura de código de barras
* Importação via planilha
* Dashboard avançado

---

## 🛠️ Tecnologias

* Frontend: Next.js
* Backend: Supabase
* Banco de dados: PostgreSQL
* Autenticação: Supabase Auth
* Hospedagem: Vercel
* Versionamento: GitHub

---

## 📂 Estrutura do projeto

```
/project-root
│
├── /app                # Aplicação (Next.js)
├── /components         # Componentes reutilizáveis
├── /lib                # Configurações e integrações (ex: Supabase)
├── /database           # Scripts SQL e estrutura do banco
├── /docs               # Documentação do projeto
├── /public             # Arquivos estáticos
├── README.md
└── package.json
```

---

## 📊 Regras de negócio

* O estoque é calculado com base em entradas e saídas:

  **estoque = entradas - saídas - perdas + ajustes**

* Tipos de movimentação:

  * Entrada
  * Venda
  * Perda
  * Ajuste

* Cada produto possui:

  * unidade de medida (kg, unidade, maço, etc.)
  * estoque mínimo
  * validade (quando aplicável)

---

## 🔄 Fluxo básico

1. Cadastrar produtos e fornecedores
2. Registrar entrada de mercadorias
3. Registrar saídas (vendas ou perdas)
4. Acompanhar estoque pelo dashboard
5. Receber alertas de estoque baixo e validade

---

## ⚙️ Como rodar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

### 2. Acessar a pasta

```bash
cd seu-repositorio
```

### 3. Instalar dependências

```bash
npm install
```

### 4. Configurar variáveis de ambiente

Crie um arquivo `.env.local`:

```
NEXT_PUBLIC_SUPABASE_URL=your_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_key
```

### 5. Rodar o projeto

```bash
npm run dev
```

---

## 🗺️ Roadmap

### Fase 1 (MVP)

* [ ] Cadastro de produtos
* [ ] Entrada de estoque
* [ ] Saída de estoque
* [ ] Controle básico

### Fase 2

* [ ] Controle de validade
* [ ] Dashboard
* [ ] Relatórios

### Fase 3

* [ ] Multiusuário
* [ ] Código de barras
* [ ] Melhorias de UI/UX

---

## 📌 Organização no GitHub

* **Issues** → tarefas e melhorias
* **Projects** → acompanhamento (Kanban)
* **Commits** → pequenas entregas frequentes

---

## 🤝 Contribuição

Contribuições são bem-vindas!

1. Fork do projeto
2. Criar uma branch (`feature/nome-da-feature`)
3. Commit das mudanças
4. Abrir um Pull Request

---

## 📄 Licença

Este projeto está sob a licença MIT.

---

## ✨ Autor

Desenvolvido para controle de estoque de hortifruti 🍎🥬
