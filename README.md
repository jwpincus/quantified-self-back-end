# quantified-self-back-end

##Setup:
 + Clone down repo
 + run `npm install`
 + run `npm install knex -g` if you haven't globally installed knex before
 + enter `psql` run `CREATE DATABASE quantified_self; CREATE DATABASE quantified_self_test;`
 + run `knex migrate:latest`
 + run `knex seed:run`
 + run knex `migrate:latest --env test`
 + to run tests `npm test`
 + to start server `npm start`
