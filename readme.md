export PATH="/usr/bin:$PATH"

sudo docker-compose down -v
sudo docker-compose down --volumes

sudo docker-compose up
sudo docker-compose up --build
sudo docker-compose build --no-cache
sudo docker-compose up --build frontend (build a single container)
sudo docker-compose up --force-recreate

sudo docker-compose restart frontend

Get into docker Container:
sudo docker ps
sudo docker exec -it laravel-app bash

sudo docker logs efb35321fc12

Node.js Backend on: http://localhost:5000/

React frontend on: http://localhost:3005/

phpMyAdmin on: http://localhost:8080

Laravel:
Error: sessions' doesn't exist

php artisan session:table
php artisan migrate

DB:
DB_CONNECTION=mysql
DB_HOST=db
DB_PORT=3306
DB_DATABASE=lollywishdb
DB_USERNAME=lollyuser
DB_PASSWORD=lollypass

Logs:
sudo docker-compose logs frontend

Weather Types:
Sunny: When the sun is shining brightly without any clouds. Example: “It’s a beautiful day outside; the weather is sunny.”

Cloudy: When the sky is covered with clouds, blocking the direct sunlight. Example: “The weather forecast predicts a cloudy day with occasional showers.”

Rainy: When water droplets fall from the clouds to the ground. Example: “Don’t forget to carry an umbrella; it’s going to be a rainy day.”

Stormy: When there are strong winds, heavy rain, and thunderstorms. Example: “Due to the stormy weather, the outdoor event has been postponed.”

Snowy: When snowflakes fall from the sky and accumulate on the ground. Example: “Children love playing in the snowy weather, building snowmen and having snowball fights.”

Windy: When there is a significant amount of wind blowing. Example: “Be careful while driving; it’s quite windy outside.”

Foggy: When the visibility is reduced due to a thick layer of fog. Example: “The foggy weather made it difficult to see the road ahead.”

Hail: When small balls of ice fall from the sky during a thunderstorm. Example: “The hailstorm damaged several cars and windows in the neighborhood.”

Temperature: The degree of hotness or coldness of the atmosphere. Example: “The temperature today is expected to reach 30 degrees Celsius.”

Humidity: The amount of moisture present in the air. Example: “The high humidity levels make the weather feel hotter than it actually is.”