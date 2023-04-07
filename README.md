## Labook 


é uma plataforma social criada para conectar pessoas e fomentar interações entre elas. Ao se cadastrar na plataforma, é possível criar e curtir publicações.

O back-end do Labook utiliza a estrutura de servidor Express e banco de dados SQLite3.

A API do Labook segue os seguintes padrões de requisição:

GET: retorna informações de um ou mais registros;
POST: utilizado para criar um novo registro;
PUT: atualiza dados de um registro ou altera sua situação;
DELETE: remove um registro do sistema.
As respostas da API são enviadas com os seguintes códigos:

200: requisição executada com sucesso;
201: recurso criado com sucesso;
400: erros de validação ou campos informados que não existem no sistema;
404: registro pesquisado não encontrado.
O banco de dados utilizado pelo Labook é ilustrado na imagem abaixo:

projeto-labook 

A documentação completa do Labook pode ser acessada pelo link abaixo:
https://documenter.getpostman.com/view/24460673/2s93XsWkUc

As tecnologias utilizadas na construção do Labook são:

Node.js;
Typescript;
Express;
Cors;
Knex;
Arquitetura em camadas;
Roteamento;
Geração de UUID;
Geração de hashes;
Autenticação e autorização;
SQLite3.

Feito por https://www.linkedin.com/in/maikel-diulio-dev/