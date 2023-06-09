# App

GymPass style app.

## RFs (Requisitos funcionais)

- [x] Deve ser possível se cadastrar;
- [ ] Dever ser possível se autenticar;
- [ ] Dever ser possível obter o perfil de um usuário logado;
- [ ] Dever ser possível obter o número de check-ins realizados pelo usuário logado;
- [ ] Dever ser possível o usuário obter seu histórico de check-ins;
- [ ] Dever ser possível o usuário buscar academias próximas;
- [ ] Dever ser possível o usuário buscar academias pelo nome;
- [ ] Dever ser possível o usuário realizar check-in em uma academia;
- [ ] Dever ser possível validar o check-in de um usuário;
- [ ] Dever ser possível cadastrar uma academia;

## RNs (Regras de negocio)

- [x] O usuário não deve se poder se cadastrar com um e-mail duplicado;
- [ ] O usuário não pode fazer dois check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in se não estiver perto(100m) da academia;
- [ ] O check-in só pode ser validado até 20 minutos após criado;
- [ ] O check-in só pode ser validado por administradores;
- [ ] A academia só pode ser cadastrada por administradores;

## RNFs (Requisitos não-funcionais)

- [x] A senha do usuário tem que estar criptografada;
- [x] Os dados da aplicação precisam estar persistidos em um banco PostgresSQL;
- [ ] Todas listas de dados precisam estar paginadas com 20 itens por página;
- [ ] O usuário dever ser identificado por um JWT(JSON Web Token);