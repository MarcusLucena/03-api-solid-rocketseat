## App

GymPass style app.

## Rfs - Requisitos funcionais

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil de um usuário logado
- [ ] Deve ser possível obter o numero de check-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário obter seu histórico de check-ins;
- [ ] Deve ser possível o usuário buscar academias próximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário realizar check-in em uma academia;
- [ ] Deve ser possível validar o check-in de um usuário;
- [ ] Deve ser possível cadastrar uma academia

## RNs - Regras de nedócio

- [ ] O usuário não deve poder se cadastrar com um e-mail duplicado;
- [ ] O usuário não pode fazer dois check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in se não esiver perto (100 metros) da academia;
- [ ] O check-in só pode ser validado até 20 minutos após criado;
- [ ] O check-in só pode ser validado por administradores
- [ ] A academia só pode ser cadastrada por administradores

## RNFs - Requisitos não funcionais

- [ ] A senha do usuário precisa estar criptografada;
- [ ] Os ados da aplicação precisam estar persistidos em banco de dados PostgreSQL;
- [ ] Todas listas de dados precisaam estar paginadas com 20 itens pode pagina;
- [ ] O usuário deve ser identificado por JWT (JSON Web Token);
