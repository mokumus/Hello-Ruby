# README


* Ruby version
    * 3.2.1
* System dependencies
    * wsl or ubuntu environment
    * postgresql -> https://www.digitalocean.com/community/tutorials/how-to-use-postgresql-with-your-ruby-on-rails-application-on-ubuntu-20-04
* Configuration
    ```bash
    bundle install
    ```
* Database creation

    ```bash

    rails db:create
    rails db:migrate

    #In postman you can send HTTP requests to localhost:3000 e.g:
    GET -> localhost:3000/groups
    POST -> localhost:3000/groups
    #Requests accepts json bodies.
    ```

* Run the local server
    ```bash
    rails server
    ```