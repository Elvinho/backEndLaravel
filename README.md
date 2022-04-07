# backEndLaravel

## criando um modelo juntamente com uma migration (migração). Para fazer isso, você precisa executar:

php artisan make:model Usuario -m

Em seguida, você pode abrir a pasta do projeto em seu editor de texto preferido e modificar o arquivo .env para inserir suas credenciais de banco de dados adequadas. Isso permitirá que o aplicativo se conecte corretamente ao banco de dados recém-criado:

## Em seguida, você executará a migração usando o seguinte comando:

php artisan migrate

#rodar 

php artisan serve
