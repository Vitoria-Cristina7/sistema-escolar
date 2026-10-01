# ❀ Sistema Escolar — Gestão de Professores ❀

> ✦ *Projeto desenvolvido para a disciplina de Programação para Internet.*

---

## ✽ Informações Acadêmicas

* **Instituição:** Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Norte (IFRN)  
* **Curso:** Técnico Integrado em Informática — 3º Ano  
* **Aluna:** Vitória Cristina  
* **Repositório:** [github.com/Vitoria-Cristina7/sistema-escolar](https://github.com/Vitoria-Cristina7/sistema-escolar)  

---

## ❁ Sobre o Projeto

O **Sistema Escolar** é uma aplicação web interativa desenvolvida em React com Vite. O objetivo desta atividade foi expandir a estrutura do sistema criando o módulo de cadastro e gestão (**CRUD**) de **Professores**, integrando com o **JSON Server** através de requisições HTTP via Axios.

---

## ✦ Funcionalidades

✧ **Listagem de Professores:** Exibição dinâmica dos professores cadastrados na API.  
✧ **Cadastro de Professores:** Formulário para inserção de novos professores no banco de dados.  
✧ **Remoção de Professores:** Exclusão individual de registros direto da listagem.  
✧ **Navegação SPA:** Roteamento entre páginas sem recarregar a tela com React Router Dom.  

---

## ✽ Estrutura dos Dados

Cada professor cadastrado no arquivo `db.json` possui a seguinte estrutura:

| Campo | Tipo | Exemplo |
| :--- | :--- | :--- |
| `id` | Número (automático) | `1` |
| `nome` | Texto | `Carlos Oliveira` |
| `email` | E-mail | `carlos@escola.com` |
| `cpf` | Texto | `987.654.321-00` |
| `disciplina` | Texto | `Programação para Internet` |
| `data_admissao` | Data | `2022-03-01` |

---

## ❁ Estrutura de Arquivos Criados & Atualizados

    src/
     ├─ services/
     │   ├─ alunoService.js
     │   └─ professorService.js ─── ✿ (Novo serviço HTTP)
     │
     ├─ components/
     │   ├─ BarraNavegacao.jsx ──── ✿ (Atualizada com novas rotas)
     │   ├─ CampoTexto.jsx
     │   ├─ CardProfessor.jsx ───── ✿ (Card de exibição do professor)
     │   ├─ FormularioProfessor.jsx ✿ (Formulário de cadastro)
     │   └─ ListaProfessores.jsx ── ✿ (Renderiza a lista de cards)
     │
     ├─ pages/
     │   ├─ PaginaInicial.jsx
     │   ├─ PaginalistagemProfessores.jsx ── ✿ (Página de listagem)
     │   └─ PaginaCadastroProfessor.jsx ─── ✿ (Página de formulário)
     │
     ├─ App.jsx ─────────────────── ✿ (Rotas e estados globais)
     └─ db.json ──────────────────── ✿ (Banco de dados simulado)

---

## ✦ Tecnologias Utilizadas

* ❀ **React + Vite** (Biblioteca para interface web)
* ❀ **React Router Dom** (Gerenciamento de rotas)
* ❀ **Axios** (Cliente HTTP para integração com a API)
* ❀ **JSON Server** (API Rest simulada)
* ❀ **CSS3** (Estilização dos componentes)

---

## ✽ Como Executar o Projeto

1. **Clone o repositório:**
    git clone [https://github.com/Vitoria-Cristina7/sistema-escolar.git](https://github.com/Vitoria-Cristina7/sistema-escolar.git)

2. **Acesse a pasta do projeto e instale as dependências:**
    cd sistema-escolar
    npm install

3. **Inicie a API simulada (JSON Server) em um terminal:**
    npx json-server --watch db.json --port 3000

4. **Inicie o projeto em outro terminal:**
    npm run dev

5. **Acesse no navegador:**  
   Abra o endereço gerado no terminal (geralmente `http://localhost:5173`).

---

<div align="center">

✿ **Desenvolvido por Vitória Cristina** ✿  
*Técnico Integrado em Informática — IFRN*

</div>
