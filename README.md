### Konfiguracja /plik .env/
Plik ten musi istnieć w katalogu głównym przed przystąpieniem do opisanych czynności w poniższych punktach.
- MAILER_DSN=native://default
- MAILER_ADDRESS=<your_email_adres>
- MAILER_NAME=<mailbot_name>
- DATABASE_URI=<your_database_connection_information>
### Instalacja
1. composer install
2. npm install
3. npm run dev
### Migracja danych
    php bin/console doctrine:migrations:migrate
### Autoryzacja
KONTO: admin@kozacki.pl HASŁO: admin
### API
- /api/posts &ensp;&ensp; Pobieranie wyszystkich postów z lokalnej bazy danych.
