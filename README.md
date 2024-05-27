
Advanced Websocket data manage-assignment

This Laravel application demonstrates the integration of websockets to provide real-time data updates to the frontend. The application generates random data every second and pushes it to the frontend using websockets.


## Table of content

- About
- Requirements
- Installation Instructions
- Usage
- Credit
- License

## Requirements

- PHP >=8.1.10.
- Laravel 10.
- Node.js >= v18.14.0.
- Composer.
- Laravel Websockets.
- Laravel Echo.
- Pusher.

## Installation

 Clone the repository:
```bash
   git clone <repository_url>
```
 Install composer dependencies:
 ```bash
  composer install
```
 Install npm dependencies:
 ```bash
 npm install && npm run dev
```
 Copy the .env.example file to .env:
 ```bash
cp .env.example .env
```
 Set up your database connection in the .env file:
 ```
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=randomdatabase
    DB_USERNAME=your_database_username
    DB_PASSWORD=your_database_password
```
 Set up the broadcasting configuration in the .env file:
 ```
    BROADCAST_DRIVER=pusher

    PUSHER_APP_ID=12345678
    PUSHER_APP_KEY=asdv
    PUSHER_APP_SECRET=adfd
    PUSHER_APP_CLUSTER=mt1
```

Import database from mySql folder locate in root directory:
```
 \Advanced-Websocket-data-manage-assignment\mySql
```
## Usage/Examples

```
Once the application is set up and running, you can visit the homepage to see the real-time updates of random data. The data consists of three columns (A, B, C), and every second, the values of these columns are updated with random numbers generated by the backend.
```


## Credits
This application is built using:

Laravel - The PHP Framework for Web Artisans

Laravel Websockets - A Laravel package to handle Websockets

Laravel Echo - JavaScript library to work with Websockets

Pusher - A hosted service that makes it super-easy to add real-time data and functionality to web and mobile applications
## License

This project is open-source software licensed under the MIT license.
