# Sistema de Login com Registro de Usuário - Django

Este projeto é um exemplo simples de como criar um sistema de registro e login de usuários utilizando o framework Django (Python). Os usuários podem criar uma conta, fazer login e fazer logout.

# ✨ Funcionalidades

- Registro de novos usuários

- Autenticação de login

- Logout

- Mensagens de feedback (sucesso, erro etc.)

# 🛠️ Tecnologias Utilizadas

- Python 

- Django 

- HTML 

- SQLite

# 🚀 Como Executar o Projeto

- Clone o repositório
   
- Aplique as migrações

    python manage.py makemigrations
   
    python manage.py migrate
   
- Rode o servidor:

    python manage.py runserver

Acesse: http://127.0.0.1:8000

# 🔐 Fluxo de Autenticação

1. Usuário acessa /signup/ para criar uma conta.

2. Após registro bem-sucedido, é redirecionado para /login/.

3. Ao fazer login, é redirecionado para a página home /home/.
   
4. O usuário pode sair da conta com /logout/.

# Principais Arquivos

views.py

Funções responsáveis por lidar com login, logout, registro e redirecionamentos.

urls.py

Rotas principais: /signup/, /login/, /home/, /logout/.
