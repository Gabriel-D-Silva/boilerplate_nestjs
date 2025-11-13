# Boilerplate

Boilerplate de NestJS com Prisma criado!

Esse projeto deve servir de base para outros projetos Nest, pois já tem configurado todo o ambiente em que o Prisma deve rodar, em conjunto com o NestJS, atualmente ele tem:

1. Um banco de dados SQLite local organizado pelo Prisma, que possui apenas uma entidade chamada 'Users'.

2. Uma API Resource que faz a comunicação do Prisma com a API Nestjs, esse resource está dentro de src/prisma.

3. Outra API Resource que contem os controllers, regras de negocio e modules envolvendo a rota de Users, com um crud básico que se comunica com o banco de dados e não permite operações em users já existentes.

4. Configuração de ambiente do Prisma de acordo com a documentação do NestJS.

5. Validação de request body com a lib class-validator e class-transformer, de acordo com a documentação do NestJS