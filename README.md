# Docker

`docker pull php:7`

`docker run -w /app -v $(pwd):/app php:7 /bin/bash -c "php php7.php"`

`docker run -w /app -v $(pwd):/app php:5 /bin/bash -c "php -r 'echo date('now');'"`

`docker run -w /app -v $(pwd):/app php:5 /bin/bash -c "php -r 'echo phpinfo();'"`

# Wordpress

`docker-compose up -d`

`http://127.0.0.1:8000`



# References:
- https://wiki.php.net/rfc/combined-comparison-operator
- https://www.youtube.com/watch?v=Q6EBPTVCrDM
- https://medium.com/@giorgioto/docker-compose-yml-from-v1-to-v2-3c0f8bb7a48e#.avgetcq9q
