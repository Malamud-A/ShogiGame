# ShogiGame
An interactive multiplayer browser-based game.  
Basic fucntions are:
* Game based on Jadokensu shogi rules
* Chat for players communication
* Board log
* User authorization
* User recent games log


## BASIC PARTS (docker containers)
* Front app
* Backend, including websockets interface
* PostgreSQL DB
* Nginx

### Front-end
* Webpack config
    * HMR
* ESlint
* Swelte
* Tests
    * Jest + Enzyme (?)

### Back-end
* Typescript
    * ts-lint
* Express
* Sequelize ORM | Type ORM (?)
* Socket.io
* AJV validation (?)
* Tests
    * Mocha + Chai (?)

### Dev-ops tools
* Docker
* Nginx
* .env config handler (?)

### Data Base
* PostgreSQL
* db schema (link: TBD)

##### Legend
* (?) - Requires additional research
* x | y - alternatives to be chosen
