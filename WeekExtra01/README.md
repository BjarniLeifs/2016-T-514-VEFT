# Extra Material for NodeJs, Postgres, JWT and Nodemailer
>Before we begin I want it to be noted that I work on OSX.

This series of extra material we will look into how to setup nodejs using express with Postgres, Json web token and nodemailer. We will look into how to implament our own authentication using JWT and how to use them on our routes. We will also look into how we can send e-mail to user, e.g. the user wants to reset password. Setup simple test and see how to use package.json scripts. 


The setup of this series is as follows:


1. Setting up project
2. Using package.json
3. Our dependencies
4. 
5. 


## Download and install
For this we need to have NodeJS installed, at this point you should have NodeJS installed, as in week09 2. Express chapter we was interduced to Express generator. However that generator has way more than we need, meaning we get view engine with it, there is another generator we can use : express generator api. Lets use that and install it globaly. 

	npm install -g express-generator-api 


As with all frameworks it is possible to use PostgreSQL with NodeJs. When looking at the project that is developed we need to ask our self what we need. Often we need [RDBMS](https://en.wikipedia.org/wiki/Relational_database) therefore it is nice to know how to use PostgreSQL with Nodejs. If you have not PostgreSQL installed already then go to [Offical PostgreSQL Website](https://www.postgresql.org) and follow the instruction on how to setup Postgres. On other note, if you are on Mac you could look at [Postgres.app](http://postgresapp.com). 


