# Exams and labs API

## Preparing DB:
- Install postgres
- Create user 'examlabs' with password 'exam@LABS.123'
- Create database examlabs
- Run createdb.js with command `node createdb`

_Feel free to change any of this details or to create tables by yourself in psql, but keep in mind to update the credentials in `config/default.json` or just erase the credentials usage in `db/index.js` and use env vars according to [node-postgres documentation](https://node-postgres.com/features/connecting)._

## Running server
Inside the root directory of the project, run the following commands:
- `npm i` (for the first run, or if the directory `node_modules` is missing)
- `npm start`

## Aditional Scripts:
- To drop all tables in db run dropdb.js with command `node dropdb`

## Postman
- All examples of routes usage is avaible in `test API.postman_collection`

## TODO:
- Imrpove this readme, with requisitions specifications
- Prevent duplicates in services