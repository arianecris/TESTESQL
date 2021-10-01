Script de criação do banco de dados Bar e Restaurante
*Primeiro criei um TableSpace BARERESTAURANTE no banco de dados para armazenar todas as informações necessárias;
*Em seguida executei o script ALTER SESSION SET "_ORACLE_SCRIPT"=TRUE para permitir a criação de usuario de banco de dados com nome mais simples;
*Criei um usuario e senha para o TABLESPACE BARERESTAURANTE;
*Usei o comando GRANT para conceder permissões ao usuario criado ao banco de dados BARERESTAURANTE;
*Alterei o usuario adicionando cotas ilimitadas de criação de objetos no banco de dados;
*Criei uma nova conexão no SQLDeveloper com usuario e senha, realizei o teste de conexão e salvei;
*Criei as tabelas que foi pedido para o teste;
*Criei as sequences para armazenar os sequenciais das chaves primarias de cada tabela;
*Fiz o insert de todos os registros de três a quatro por tabela;
*Fiz o select para exibir os pedidos e os itens do pedidos, usei o join para fazer as junçoes das tabelas relacionadas;
*Fiz o diagrama DER.
