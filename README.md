# Zadanie 2

Polecenie uruchamiające stack: ```docker compose up -d```

Polecenie uruchamiające phpMyAdmin: ```docker compose up -d phpmyadmin```

Polecenie tworzące testową bazę test3: ```docker exec zadanie2-mysql-1 mysql --execute "CREATE DATABASE test3" --user=root --password=root```

Polecenie generujące plik ilustrujący strukturę projektu: ```docker container run --rm -it --name mgraph -v $(pwd):/input pmsipilot/docker-compose-viz render -m image docker-compose.yml```

![Uruchomienie](./zadanie2/zad2_1.JPG)

![Uruchomienie](./zadanie2/zad2_4.JPG)

PhpMyAdmin:

![Uruchomienie](./zadanie2/zad2_2.JPG)

Strona index.php

![Uruchomienie](./zadanie2/zad2_3.JPG)

Struktura projektu:

![Struktura](docker-compose.png)
