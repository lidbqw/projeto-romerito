🍷 Vinhedo Online – Loja de Vinhos
Este projeto é uma aplicação web desenvolvida em Flask + SQLAlchemy, com o objetivo de simular um site de vendas de vinhos.
Ele permite o cadastro e login de usuários, além do gerenciamento completo de produtos (CRUD).

✨ Funcionalidades:
- Cadastro e Login de Usuários:
  - Registro com nome, e-mail e senha
  - Login simples validando credenciais
  - Sessão mantida até logout

- Gerenciamento de Vinhos (CRUD):
  - Cadastrar vinhos (nome, preço, descrição)
  - Listar produtos em uma tabela
  - Editar informações
  - Excluir produtos

- Interface:
  - Templates com Jinja2
  - Páginas mínimas:
    - `index.html` → Página inicial
    - `login.html` → Login de usuários
    - `cadastro_usuario.html` → Registro de usuários
    - `produtos.html` → Listagem e CRUD

📂 Estrutura do Projeto:
vinhedo/
├── app.py 
├── banco.py
├── templates/
│ ├── index.html
│ ├── login.html
│ ├── cadastro.html
│ ├── produtos.html
├── static/
│ ├── css/
│ └── img/
├── requirements.txt
└── README.md

- Funcionalidades
. Cadastro e Login de Usuários
. Registro com nome, e-mail e senha.
. Login simples validando e-mail e senha.
. Sessão mantida até logout.
. Gerenciamento de Produtos (CRUD)

- Cadastro de vinhos com:
. Nome
. Preço
. Descrição
. Edição e exclusão de produtos.

- Interface
. Estrutura básica de páginas:
    - index.html → Página inicial
    - login.html → Login de usuários
    - cadastro_usuario.html → Registro de usuários
    - produtos.html → Listagem e CRUD de vinhos

- Tecnologias Utilizadas:
. Python 3
. Flask
. SQLAlchemy
. HTML

- Como Executar o Projeto:
1. Clone o repositório: git clone https://github.com/seu-usuario/vinhedo-online.git
cd vinhedo-online
2. Crie e ative ambiente virtual:
python3 -m venv venv
source venv/bin/activate   # Linux / Mac
venv\Scripts\activate      # Windows
3. Instale dependências:
pip install -r requirements.txt
4. Rode a aplicação
5. Acesse em -> http://127.0.0.1:5000

👨‍💻 Autores:
César, Godofredo, Jacioneide e Lídia.
Projeto desenvolvido como atividade prática de Flask + SQLAlchemy.
📅 2025
