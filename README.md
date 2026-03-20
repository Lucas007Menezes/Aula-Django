# 🎓 Aula Django

Projeto desenvolvido durante aulas de **Django**, com foco no aprendizado dos fundamentos do framework web mais popular do Python.

## 📋 Sobre o Projeto

Uma aplicação web construída com **Django 6.0** que implementa um sistema básico com:

- 🏠 **Página Inicial** — Página pública de boas-vindas com navegação para login e cadastro
- 🔐 **Autenticação** — Módulo dedicado com páginas de **Login** e **Cadastro de Usuário**
- ⚙️ **Painel Admin** — Interface administrativa nativa do Django

## 🏗️ Estrutura do Projeto

```
Aula-Django/
├── core/               # Configurações do projeto Django
│   ├── settings.py     # Configurações gerais
│   ├── urls.py         # Rotas principais
│   ├── wsgi.py         # Configuração WSGI
│   └── asgi.py         # Configuração ASGI
├── index/              # App da página inicial
│   ├── views.py        # View da home
│   ├── urls.py         # Rotas da home
│   └── templates/
│       └── index.html  # Template da página inicial
├── autenticacao/       # App de autenticação
│   ├── views.py        # Views de login e cadastro
│   └── urls.py         # Rotas de autenticação
├── manage.py           # Utilitário de linha de comando do Django
└── db.sqlite3          # Banco de dados SQLite
```

## 🚀 Como Executar

### Pré-requisitos

- [Python 3.10+](https://www.python.org/downloads/)
- pip (gerenciador de pacotes do Python)

### Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/Lucas007Menezes/Aula-Django.git
   cd Aula-Django
   ```

2. **Crie e ative o ambiente virtual**
   ```bash
   python -m venv venv

   # Windows
   venv\Scripts\activate

   # Linux / macOS
   source venv/bin/activate
   ```

3. **Instale as dependências**
   ```bash
   pip install django
   ```

4. **Execute as migrações**
   ```bash
   python manage.py migrate
   ```

5. **Inicie o servidor de desenvolvimento**
   ```bash
   python manage.py runserver
   ```

6. **Acesse no navegador**
   ```
   http://127.0.0.1:8000/
   ```

## 🗺️ Rotas da Aplicação

| Rota | Descrição |
|------|-----------|
| `/` | Página inicial pública |
| `/auth/login/` | Página de login |
| `/auth/cadastro/` | Página de cadastro |
| `/admin/` | Painel administrativo do Django |

## 🛠️ Tecnologias Utilizadas

- **Python** — Linguagem de programação
- **Django 6.0** — Framework web
- **SQLite** — Banco de dados
- **HTML** — Templates

## 📚 Conceitos Aprendidos

- Criação de projeto e apps no Django
- Sistema de rotas (URLconf) com `include`
- Views baseadas em funções (FBV)
- Renderização de templates HTML
- Organização modular do projeto
- Ambiente virtual com `venv`

## 📄 Licença

Este projeto é de uso educacional, desenvolvido durante aulas de Django.

---

