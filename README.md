
        composer install

        npm install

        cp .env.example .env
		
		mysql database içinden yeni bir veritabanı oluşturup veritabanı bilgilerinin ve bağlantı bilgilerini .env dosyası içinden değiştirin.
		
        php artisan migrate:fresh --seed

        php artisan key:generate

        php artisan serve
