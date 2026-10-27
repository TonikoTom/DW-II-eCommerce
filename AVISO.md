# Painel E-commerce 🛍️

Painel administrativo e sistema de e-commerce desenvolvido com PHP, JavaScript e Bootstrap.

---

## 🚀 Configuração do Ambiente e Banco de Dados

Como o banco de dados foi configurado localmente na máquina, siga os passos abaixo para configurar o ambiente corretamente caso vá testar o código em outro computador:

### 1. Acessar o phpMyAdmin
1. Inicie o seu servidor local (ex: USBWebserver).
2. Acesse o **phpMyAdmin** utilizando as credenciais padrão:
   - **Usuário:** `root`
   - **Senha:** `usbw`

### 2. Criar o Banco de Dados
Crie um novo banco de dados com o seguinte nome:
* **Database:** `ecommerce`

### 3. Criar as Tabelas
Dentro do banco de dados `ecommerce`, crie as seguintes tabelas essenciais:

* **`usuarios`**: Armazena as credenciais de acesso (e-mail e senha) para autenticação no painel.
* **`produtos`**: Armazena os itens disponíveis para venda exibidos no sistema.

---

## 🛠️ Tecnologias Utilizadas
* **PHP** (Back-end / APIs)
* **JavaScript** (Requisições assíncronas via `fetch`)
* **Bootstrap 5** (Interface e Estilização)
* **MySQL / phpMyAdmin** (Banco de Dados)
