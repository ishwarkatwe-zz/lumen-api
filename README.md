# lumen-api


Clone / Download zip
 
    composer update
Generate App Key

    php artisan key:generate

Generate JWT Key

    php artisan jwt:secret
    
    
Create user table migration with demo user seed for testing

    Ex: admin@demo.com
    Pw: 123456

Auth with credentials
    
    curl -i http://localhost:8080/auth/login -d email=admin@demo.com -d password=123456
    
    Response with token
    
Auth with signed Token

    curl -H "Authorization: Bearer <token>" http://localhost:8080


       
       
       
