# Secret Santa

This project is based on Secret Santa, a game which consists of exchanging gifts among friends.

The organizer provides all the email addresses, and the app randomly assigns a "presentee" to each person.

Each person will later receive an email with the information about the presentee.
## Getting Started
### Prerequisites

This app is docker based. To avoid extra configurations, you should have `docker` and `docker-compose` installed. 

If you don't want to install these softwares, you will be able to use this app installing `ruby` (>= 2.3) and `Postgresql` (>= 9.5).
### Installing

* Clone this repo `git clone https://github.com/aline-aline/ruby-chat`;
  * In the repo folder, run: 
    * `docker-compose build`;
    * `docker-compose run --rm app bundle exec rake db:create`;
    * `docker-compose run --rm app bundle exec rake db:migrate`.
## Running the tests

```
docker-compose run --rm website bundle exec rspec spec
```
## Built With

* Ruby On Rails: http://rubyonrails.org/
* PostgreSQL: https://www.postgresql.org/
* Redis: https://redis.io/
* Docker: https://www.docker.com/
* Docker-Compose: https://docs.docker.com/compose/

## Contributing

Want to contribute? Fork and send a pull request. Have any questions? Open an issue or contact me.
## License

This project is licensed under the MIT License.

