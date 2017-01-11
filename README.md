
# Java-Sockets

L' obbitettivo del progetto è di inviare linee di testo da un programma (Client) ad un altro (Server) anche eventualmente remoto.


### Prerequisiti
Java SDK (Software Development Kit) - programma per la compilazione (javac) da codice in Java a ByteCode. L'installazione comprende anche Java JRE (Java Runtime Envirorment) che fornisce la Virtual Machine (VM) su cui far eseguire il ByteCode.
```
E' suggerito anche l'utilizzo di netBeans IDE (Integrated Development Envirorment)
```

### Installazione
Scarica i files del progetto cliccando "Clone/Download"
* in NetBeans crea due nuovi progetti "Java-Sockets-Client" e "Java-Sockets-Server"

* estrai i files e spostali nella sub-directory "src" dei rispettivi progetti (es. Documents\NetBeansProjects\Java-Sockets-Server\src)

### Esempio usando stesso computer sia per eseguire Server che multipli Clients
Da finestra di comando esguire il Server:
```
cd Documents\NetBeansProjects\Java-Sockets-Server\src
java ServerTestoMultiThreaded 1234
```
Da nuova finestra di comando esguire il ```primo``` Client
```
cd Documents\NetBeansProjects\Java-Sockets-Client\src
java client-Testo localhost 1234
```
Da nuova finestra di comando esguire il ```secondo``` Client
```
cd Documents\NetBeansProjects\Java-Sockets-Client\src
java client-Testo localhost 1234
```

## Licenza
Opensource.

##Patch Notes
versione 1.2:
```
-Aggiunta la disconnessione dell' utente dalla chat tramite il comando ctrl+c
```



##Autori 
Rinaldi Brescia Monteleone

