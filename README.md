# Prontuario laravel

## Avvio di un progetto

### Creazione di un nuovo progetto da zero
`composer create-project --prefer-dist laravel/laravel:^7.0 nome-progetto`

`composer install`

`npm install`

### Clone di un progetto da github
`dopo aver fatto il clone...`

`composer install`

`npm install`

`copia del file .env.example su .env`

`personalizzazione del file .env`

`php artisan key:generate`

`php artisan db:seed`

`php artisan migrate`

## Comandi Artisan

### Lista di tutte le funzioni di artisan
`php artisan list`

### Creazione della chiave di crittografia
`php artisan key:generate`

### Lista di tutte le rotte
`php artisan route:list`

### Creazione di un nuovo model
`php artisan make:model NomeModello`

### Creazione di un nuovo controller
`php artisan make:controller NomeController`

### Creazione di un nuova migration (creazione tabella)
`php artisan make:migration create_xxx_table`

### Creazione di un nuova migration (aggiornamento tabella)
`php artisan make:migration update_xxx_table --table=xxx`

### Lancio migrazioni
`php artisan migrate`

### Annullo ultima migrazione
`php artisan migrate:rollback`

### Creazione Seeder
`php artisan make:seeder NomeSeeder`

### Lancio Seeder Specifico
`php artisan db:seed --class=NomeSeeder` 

### Lancio Seeder Base
`php artisan db:seed`
