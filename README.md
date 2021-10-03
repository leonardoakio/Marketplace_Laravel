<div align='right'>
    <a href="./README.md">Inglês |</a>
    <a href="./PORTUGUESE.md">Português</a>
</div>

<div align='center'>
    <h1>Marketplace</h1>
    <a href="https://www.linkedin.com/in/leonardo-akio/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn%20-blue?style=flat&logo=linkedin&labelColor=blue" target="_blank"></a> 
    <img src="https://img.shields.io/badge/version-v0.1-blue"/>
    <img src="https://img.shields.io/github/contributors/akioleo/Marketplace_Laravel"/>
    <img src="https://img.shields.io/github/stars/akioleo/Marketplace_Laravel?style=sociale"/>
    <img src="https://img.shields.io/github/forks/akioleo/Marketplace_Laravel?style=social"/>
    <img src="https://img.shields.io/badge/License-MIT-blue"/>
</div>
<br>

The project is based on a marketplace with `laravel 6`, where we have a stores and products registration, with routes for admin, shopkeepers and the store itself, where customers can make purchases directly on the system.

## Table of Contents
- [Getting Started](#getting-started)
	- [Installation](#installation)
	- [Configuration](#configuration)
- [Development](#development)
    - [Part 1: Heading](#part-1-heading)
	  - [Step 1: Subheading](#step-1-subheading)
	- [Part 2: Heading](#part-2-heading)
- [Contributing](#contributing)
- [Versioning](#versioning)
- [License](#license)

## Getting Started
Open and view the Project using the `.zip` file provided
<br/>
Or to get started, clone the repository to your directory

    git clone https://github.com/akioleo/Marketplace_Laravel.git
    
Start the local development server

    php artisan serve
    

### Installation
Install all the dependencies using composer

    composer install
    
Generate a new artisan key

    php artisan key:generate


### Configuration
Create a new *.env* archive based on *.env.example*

    php -r "copy('.env.example', '.env');

In new `.env` file type your database credentials in these lines<br/>
*Obs: **DB_CONNECTION** changes by the database used. Example: Postgre database (**pgsql**)*

    DB_CONNECTION=mysql  
    DB_HOST=127.0.0.1  
    DB_PORT=3306  
    DB_DATABASE=laravel  
    DB_USERNAME=root  
    DB_PASSWORD=
 

Include personal <a href="https://acesso.pagseguro.uol.com.br/sandbox">PagSeguro</a> credentials

    DB_CONNECTION=mysql  
    DB_HOST=127.0.0.1  
    DB_PORT=3306  
    DB_DATABASE=laravel  
    DB_USERNAME=root  
    DB_PASSWORD=
 
Run the database migrations to create predefined database tables 

    php artisan migrate  
    
Run seeds to populate the database with data we want to develop in future

    php artisan db:seed  

## Development

This section is completely optional. For big projects, the developement strategies are not discussed. But for small projects, you can give some insight to people. It has 2 benefits in my opinion:

1. It's a way to give back to the community. People get to learn from you and appreciate your work
2. You can refer the README in future as a quick refresher before an interview or for an old project to check if it can help you in your currect work

### Part 1: Heading

#### Step 1: Subheading

* Mention the steps here
  * You can also have nested steps to break a step into small tasks
  
#### Step 2: Subheading

* Mention the steps here.
  * You can also have nested steps to break a step into small tasks

For details now how everything has been implemented, refer the source code

### Part 2: Heading

* Mention the steps here

## Contributing

Mention what you expect from the people who want to contribute

We'd love to have your helping hand on `Project Title`! See [CONTRIBUTING.md] for more information on what we're looking for and how to get started.

## Versioning

If your project has multiple versions, include information about it here. 

For the available versions, see the [tags on this repository][tags]

## License

`Marketplace` is open source software [licensed as MIT][license].

[license]: https://github.com/akioleo/Marketplace/blob/master/LICENSE.md
