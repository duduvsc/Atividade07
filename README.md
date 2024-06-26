Sistema de Gerenciamento de Eventos
Este projeto consiste em um sistema de gerenciamento de eventos desenvolvido utilizando Node.js, Express e React.

Atividade
Desenvolvimento de um Sistema de Gerenciamento de Eventos

Objetivo
Desenvolver um sistema web para gerenciar eventos, permitindo a criação, leitura, atualização e exclusão de eventos, além de funcionalidades de autenticação e autorização de usuários.

Descrição
Este sistema foi criado para atender às necessidades de uma empresa na organização de eventos internos e externos. Ele oferece as seguintes funcionalidades principais:

Funcionalidades
Autenticação e Autorização de Usuários:

Registro e login de usuários utilizando JSON Web Tokens (JWT).
Middleware para proteger rotas que exigem autenticação.
Diferenciação de permissões entre usuários comuns e administradores.
CRUD de Eventos:

Criação, leitura, atualização e exclusão de eventos.
Informações detalhadas de cada evento incluem título, descrição, data, local e organizador.
Validação dos dados de entrada para garantir consistência.
Gerenciamento de Participantes:

Registro de usuários como participantes de eventos.
Visualização e gerenciamento da lista de participantes por administradores.
Integração com MongoDB:

Utilização do MongoDB para armazenamento de dados de usuários, eventos e participantes.
Modelagem de dados utilizando Mongoose para facilitar a interação com o banco.
API RESTful:

Implementação de uma API RESTful com endpoints bem definidos para interação com o sistema.
Documentação da API utilizando Swagger para facilitar o entendimento e uso por outros desenvolvedores.
Interface de Administração com React:

Desenvolvimento de uma interface de administração responsiva utilizando React.
Consumo da API RESTful no backend para gerenciar eventos e participantes.
Componentes para login, registro, listagem de eventos, formulário de criação/edição de eventos e gerenciamento de participantes.
Estilização e UX:

Aplicação de estilos adequados aos componentes React utilizando Styled Components.
Interface responsiva, garantindo uma boa experiência de usuário em dispositivos desktop e mobile.
Requisitos Técnicos:

Backend desenvolvido com Node.js e Express.
Banco de dados MongoDB utilizado para persistência de dados.
JWT para autenticação de usuários.
Mongoose para modelagem de dados MongoDB.
Documentação da API utilizando Swagger.
Frontend desenvolvido em React, consumindo dados da API através de Axios.
Redux utilizado opcionalmente para gerenciamento de estado da aplicação