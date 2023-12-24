# Backend para Autenticação e Páginas
Este repositório contém o backend Node.js que se integra ao frontend para autenticação de usuários. Ele utiliza o MongoDB para armazenar contas de usuários e autenticação baseada em cookies.

# Funcionalidades
Registro de Conta: Os usuários podem se registrar fornecendo informações como nome de usuário, e-mail e senha.

Login: Os usuários podem fazer login usando suas credenciais existentes.

Persistência de Dados: As contas de usuários são armazenadas no MongoDB.

Autenticação de Cookies: A autenticação é realizada por meio de cookies para manter os usuários conectados.

Criptografia de senha: A criptografia é realizada usando bcrypt.

# Tecnologias Utilizadas
Node.js: Ambiente de execução para JavaScript.

Express: Framework web para Node.js.

MongoDB: Banco de dados NoSQL para armazenamento de dados.

Mongoose: ODM (Object Data Modeling) para MongoDB.

Bcrypt: Criptografia de senha para armazenamento seguro.
