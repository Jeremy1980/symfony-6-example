### Instalacja
1. composer install
2. npm install
3. npm run dev
### Migracja danych
    php bin/console doctrine:migrations:migrate
## Konfiguracja /plik .env/
- MAILER_DSN=native://default
- MAILER_ADDRESS=<your_email_adres>
- MAILER_NAME=<mailbot_name>
### Autoryzacja
KONTO: admin@kozacki.pl HASŁO: admin
### API
- /api/posts &ensp;&ensp; Pobieranie wyszystkich postów z lokalnej bazy danych.
