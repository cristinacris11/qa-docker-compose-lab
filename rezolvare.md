# REZOLVARE

## Screenshot Adminer

![Tabelul tests](Tema 3- docker/rezolvare.png)

## Importanța folosirii flag-ului `-v` în `docker compose down`

Folosirea opțiunii `-v` la comanda `docker compose down -v` șterge toate volumele asociate containerelor, inclusiv baza de date și datele persistente.  
Într-un flux de lucru QA, acest lucru este important pentru a asigura un mediu curat la fiecare testare, evitând efectele datelor reziduale de la rulări anterioare și prevenind posibile erori sau inconsecvențe în testele automate.