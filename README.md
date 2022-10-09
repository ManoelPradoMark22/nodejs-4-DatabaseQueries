Nesse desafio, você realizará consultas no banco de dados com o TypeORM de três maneiras:

- Usando o ORM
- Usando Query Builder
- Usando Raw Query

Isso irá te ajudar a entender e exercitar os diferentes tipos de consultas que podemos fazer.

No template, você irá encontrar uma aplicação já estruturada (apenas as entidades e repositórios) onde você deverá completar o que falta nas consultas dos dois repositórios.

A aplicação possui dois módulos: `users` e `games`. Um **usuário** pode ter vários jogos e um mesmo **jogo** pode estar associado a vários usuários.

---

- [x] Repositories [UsersRepository] should be able to find user with games list by user's ID;
- [x] Repositories [UsersRepository] should be able to list users ordered by first name;
- [x] Repositories [UsersRepository] should be able to find user by full name;
- [x] Repositories [GamesRepository] should be able find a game by entire or partial given title;
- [x] Repositories [GamesRepository] should be able to get the total count of games;
- [x] Repositories [GamesRepository] should be able to list users who have given game id.