<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

#
# DISCORD BOT - README
#

# rpg-discord-bot
- Para rodar o projeto (hot reload): `npm run dev`
- Para rodar o projeto (produção): `npm run start`

# Versões e dependencias instaladas
  - Discord version: 12.5.3
    - `npm install discord.js 12.5.3`
  -Node version: v14.17.0
    - link de acesso: "https://nodejs.org/en/download/"

# Discord RPG
 A base de nosso projeto e criar uma estrutura de código auto o suficiente e bem setorizado, ou seja criar um código que seja de facil manuntenção e grande modularidade.

 # Ferramentas de Organização
  -Organização de Atividades
    - https://www.taskade.com/invites/T7yEAFxUej1vKbRj (Sugestão do Fabio)
  - Design WEB
    - https://www.figma.com/ (Segestão de Roberto e Vitor)

# Layout base da programação
  - https://github.com/yLost/DiscordBOT-base (Sugestão de Lost)

# Mudanças e coisas a serem discutidas
  - Reformulação dos comandos no bot;
    - Criar uma ficha - (!creatUser (nome do personagem))
    - Deleta uma ficha -(!deletUser (nome do personagem))
    - Definir Mestrante's -(!setGameMaster @mention)
    - Informação de usuário -(!userInfo @usermention)
    - Rolagem de dados - (!roll d(Qualquer valor entre 2 e 100))
    - Rolagem de multiplos dados - (!roll XdV(sendo X a quantidade de dados e V a quantidade de lados))
    - Rolagem de dados de corpo - (!roll body(braços, pernas, cabeça e etc))
    - Registra uma mesa de rpg - (!creatTable (nome da mesa))
    - Demais comandos a serem discutidos.

  - Criar um design de mensagens embed no discord.
  - Sistema de criação de cargos(Definir o mestrante e jogadores);

# Banco de Dados
  - Vincular todos os nossos dados (Guild ID, USER ID - dentre outros) a um banco de dados;
    - Escolher um BD a ser utilizado mySQl ou PostgreSQL
    - Criar tratamento de dados.
    - Sistema de backup automatico(semanal).

  - Outras coisas vão sendo discutidas com o decorrer do projeto;

# Interface Web do bot
 - Criar pagina web contendo
    Pagina web que ira conter toda a interface para o mestrante e jogador durante uma mesa do rpg podendo ser editada em tempo real.
    - pagina para ficha do personagem do usúario somente podendo ver ele e o mestrante
      - Foto do personagem
      - Foto do usuario + ID 
      - Nome do servidor em que a ficha está salva
      - Ficha do personagem contendo
        - Vida
        - Estamina
        - Dinheiro
        - Experiencia
        - Atributos de ficha
           -Constituição
           -destresa
           -sabedoria 
           -percepção 
           -inteligencia
           -carisma;
        - outros recursos extras que podem ser colocados para revisar depois.
# Informações extras
  - Demais coisas vamos discutindo
  
