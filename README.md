# DonDeSangApplication 

## dossier DonDeSang
* 1- installer docker
* 2- run docker
* 3- ouvrir CMD
* 4- executer docker pull postgres:alpine
* 5- executer docker pull redis:latest
* 6- docker run -it --rm  postgres DonDeSang-U postgres
* 7- docker run --name DonDeSangredis -d redis
* 8- ouvrir le dossier avec visual studio code 
* 9- run npm install
* 10- run php artisan serve --host 0.0.0.0
* 11- ouvrir nouveau terminal 
* 12- run  npm run io
#### Note :  il faux creer une aministrateur pour connecter : 
* => run php artisan tinker
* => run Admin::create(['nom'=>'admin1','email'=>'admin@gmail.com','password'=>Hash::make('admin')])
## dossier DonDeSangClient
#### Note : il faux desactiver le pare feu
* 1- ouvrir le dossier avec vs code
* 2- run npm install
* 3- run npm start
* 4- installer expo GO dons votre telephone
* 5- scaner le QRCode
