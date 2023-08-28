
# Oxford International School Task

Survay Form genarate & sharing system
## Deployment

To deploy this project run

### First setup the backend site on your local

```bash
  cd /server
```

On your local sever please install php version 8.1.* & composer

```bash
  php --version
  composer install
```

Copy .env.example and paste it on root paste as .env

```bash
    cp .env.example .env
```

Configur your mysql Database connection in .env file

```bash
    DB_DATABASE=vue_server
    DB_USERNAME=root
    DB_PASSWORD=
```

Migrate your Database with command

```bash
    php artisan migrate
```

Then run on local server

```bash
    php artisan serve
```

### Second setup the fronend site on your local

```bash
  cd /client
```

On your local sever please install node version 18^

```bash
    npm install
```

Copy .env.example and paste it on root paste as .env

```bash
    cp .env.example .env
```

Configur your backend api endpoint url on .env key VITE_BACKEND_URL

```bash
    VITE_BACKEND_URL=http://localhost:8000/api
```

then run npm sever

```bash
    npm run dev
```



## Environment Variables

To run this project, you will need to add the following environment variables to 

### your frontend .env file

`VITE_BACKEND_URL`=http://vue-server.test/api or your backend server url

`VITE_SOME_KEY`=123


### your backend .env file

`APP_NAME`=Laravel

`APP_ENV`=local

`APP_KEY`=base64:eG0fra+GSexhJmWkCjvQ0ARtQ+DrHpvnMxeLb5n/VVk=

`APP_DEBUG`=true

`APP_URL`=http://vue-server.test  or http://locahost:8000



`DB_CONNECTION`=mysql

`DB_HOST`=127.0.0.1

`DB_PORT`=3306

`DB_DATABASE`=vue_server or your DB name

`DB_USERNAME`=root

`DB_PASSWORD`=


## Feedback

If you have any feedback, please reach out to us at syedshazeedul@gmail.com
Otherway please vist my portfolio http://shazeedul.dev

