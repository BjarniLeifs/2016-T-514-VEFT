# Extra Material for NodeJs, Postgres, JWT and Nodemailer
>Before we begin I want it to be noted that I work on OSX.

This series of extra material we will look into how to setup nodejs using express with Postgres, Json web token and nodemailer. We will look into how to use implament our own authentication using JWT and how to use them on our routes. 

The setup of this series is as follows:


1. Setting up project
2. 
3. 
4. 
5. 


## Download and install
For this we need to have NodeJS installed, at this point you should have NodeJS installed, as in week09 2. Express chapter we was interduced to Express generator. However that generator has way more than we need, meaning we get view engine with it, there is another generator we can use : express generator api. Lets use that and install it globaly. 

	npm install -g express-generator-api 


As with all frameworks it is possible to use PostgreSQL with NodeJs. When looking at the project that is developed we need to ask our self what we need. Often we need [RDBMS](https://en.wikipedia.org/wiki/Relational_database) therefore it is nice to know how to use PostgreSQL with Nodejs. If you have not PostgreSQL installed already then go to [Offical PostgreSQL](https://www.postgresql.org) and follow the instruction on how to setup Postgres. On other note, if you are on Mac you could look at [Postgres.app](http://postgresapp.com). 









# NodeJs and PosgreSQL
[PostgreSQL](https://www.postgresql.org) is a powerful, open source object-relational database system.



By know we should have some knowledge on how to build simple API with NodeJS and Express, if that is not the case then perhaps a good next step would be to read 1. NodeJS and 2. Express in week09. Then perhaps read the documentation for NodeJS and Express.

## Download and install. 

Assuming you already have Nodejs and Express installed, we will only need to install [PostgreSQL](https://www.postgresql.org), go to the official site and follow their instruction on how to setup. 

If your'e on Mac you could check out [Postgres.app](http://postgresapp.com).


## 


With your Postgres server up and running on port 5432, making a database connection is easy with the pg library: