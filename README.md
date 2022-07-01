# knex-with-prestart-sample
Use npm prestart to automatically run the migrations for your mysql database.  You can read the full article at the following link: https://webdev201.com/articles/take-advantage-of-npm-prestart-with-knex

## Setup
To run the project create a .env file in the root directory with the following variables:

```bash
PORT=4000
DB_HOST=localhost
DB_CLIENT=mysql2
DB_USER=root
DB_PASSWORD=password
DB_DATABASE=prestart
DB_PORT=3306
```

Next install the depdendies with the following command:
```bash
npm install
```

After the dependencies have been installed you can run the project by executing
```bash
npm start
```
