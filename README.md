## Projeto desenvolvido na disciplina DM110 - Desenvolvimento Java EE

Neste projeto foi utilizado os conceitos aprendidos em aula sobre:

- Java EE
- Enterprise JavaBeans
- Java Persistence API
- Processamento de mensagens MDB.

O projeto possui duas especificações:

**1.** Serviços REST, Session Bean Stateless e Entities que suportam as seguintes operações:
- inclusão de um registro
- busca de um registro através do seu identificador (CNPJ)
- listagem de registros
- atualização de um registro

>Os serviços REST chamam o Session Bean para acessar o banco de dados.
O Session Bean chama o serviço de mensagem para ele efetuar o serviço de auditoria.

**2.** Serviço de mensagem (MDB) que efetua um registro de auditoria.
>O MDB chama um Session Bean para acessar o banco de dados.
