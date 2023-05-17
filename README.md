# Prontuario laravel

## Avvio di un progetto

### Creazione di un nuovo progetto da zero
`composer create-project --prefer-dist laravel/laravel NOME-PROGETTO "9.*"`

`composer require pacificdev/laravel_9_preset`

`php artisan preset:ui bootstrap`

`npm install`


### Clone di un progetto da github
`dopo aver fatto il clone...`

`composer install`

`npm install`

`crezione del DB con phpmyadmin`

`copia del file .env.example su .env`

`personalizzazione del file .env`

`php artisan key:generate`

`php artisan migrate`

`php artisan db:seed --class=NOME_CLASSE`

### Avvio di un progetto

`php artisan serve`

## Avvio di Vite in modalità di sviluppo
`npm run dev`

## Compilazione degli assets per la produzione
`npm run dist`

## Comandi Artisan

### Lista di tutte le funzioni di artisan
`php artisan list`

### Creazione della chiave di crittografia
`php artisan key:generate`

### Lista di tutte le rotte
`php artisan route:list`

### Creazione di un nuovo model
`php artisan make:model NomeModello`

### Creazione di un nuovo model e relativa migration
`php artisan make:model NomeModello -m`

### Creazione di un nuovo controller
`php artisan make:controller NomeController`

### Creazione di un nuovo controller (per resource controller)
`php artisan make:controller NomeController -r`

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

### Esecuzione di tutti i Seeder
`php artisan db:seed`

### Esecuzione Seeder Specifico
`php artisan db:seed --class=NomeSeeder` 


