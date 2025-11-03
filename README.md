## 1. Introdução  
O EleDom é um sistema web desenvolvido para gerenciar ordens de serviço para a empresa Eletrônica Domingos, localizada no sul de Santa Catarina, no município de Sombrio. Ele permite registrar ordens de serviço com clientes e aparelhos, acompanhar o andamento das ordens com atualização de status e visualizar ordens de serviço concluídas e canceladas, automatizando o processo de registros da empresa, anteriormente feito de forma manual.

## 2. Tecnologias Utilizadas  
- **Backend:** Node.js e Express  
- **Frontend:** HTML5, CSS3, Bootstrap e EJS  
- **Banco de Dados:** MySQL  
- **Linguagem:** JavaScript  
- **Arquitetura:** MVC (Model-View-Controller)  

## 3. Instalação  
1. Clone o repositório:  
   ```bash
   git clone https://github.com/vanny-vanessao/EleDom.git
   cd EleDom
   npm install
2. Configure o banco de dados MySQL e execute o script SQL.
3. Crie um arquivo .env na raiz do projeto com as credenciais do banco e porta do servidor, por exemplo:
   ```bash
   DB_HOST= localhost
   DB_USER= root
   DB_PASSWORD= sua_senha
   DB_NAME= EleDom
   PORT= 3000
5. Inicie o servidor:
   ```bash
   npm start
6. Acesse no navegador: http://localhost:3000

## 4. Funcionalidades Principais
-  Cadastro e login de funcionários/usuários;
-  Registro e gerenciamento de ordens de serviço;
-  Criação, edição, cancelamento e conclusão de ordens de serviço;
-  Atualização de status e histórico de atendimentos;
