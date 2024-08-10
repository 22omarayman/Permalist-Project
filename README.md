Make sure to have Node.js and pgAdmin for postgreSQL installed

type these commands in pgAdmin:
CREATE TABLE items(
	id SERIAL PRIMARY KEY UNIQUE,
	title VARCHAR(100)
);
INSERT INTO items(id,title) VALUES(1,'Buy milk'),(2,'Finish homework');


Commands in your terminal(for help):
npm init -y
npm i express
npm i body-parser
npm i pg
cd "path of the folder the files are saved"
nodemon index.js 
run server on the browser with "localhost:3000"
