LidarDriver

--- INTRODUZIONE ---
Il seguente progetto è parte del corso di Laboratorio di Programmazione (progetto intermedio). È stato svolto dal gruppo "_sudo rm -rf /*" (underscore per motivi di sicurezza).
Il progetto LidarDriver è un'applicazione progettata per gestire e simulare il funzionamento di un driver LIDAR.

--- STRUTTURA DEL PROGETTO ---
La seguente struttura del progetto è suddivisa in più file per questioni di modularità e semplicità di gestione del codice:

LidarDriver:
├── include
│     └── lidardriver.h
├── README.txt
└── src
      ├── main.cpp
      └── lidardriver.cpp

di cui:
> lidardriver.h è un header file: contiene la dichiarazione delle funzioni e della classe sviluppata e utilizzata nel progetto;
> lidardriver.cpp è un implementation file: implementa le funzionalità dichiarate nell'header file;
> main.cpp: punto di ingresso del programma, gestisce l'interazione utente e l'esecuzione generale. In questo caso, è utilizzato come test per la classe.