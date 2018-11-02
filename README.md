# teste_rodrigo

# Framework Laravel 

# Etapas para instalação da aplicação

1º Colocar as credenciais do BD Mysql no .env
	
	DB_CONNECTION=mysql
	DB_HOST=127.0.0.1
	DB_PORT=3306
	DB_DATABASE=teste_rodrigo
	DB_USERNAME=root
	DB_PASSWORD=
	
2º php artisan mysql:createdb teste_rodrigo
3º colocar o nome do bd no .env
4º php artisan migrate:install
5º php artisan migrate
6º php artisan serve

