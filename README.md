# Server Web Simplu in C

Acest proiect este un server web elementar scris in C. 
Demonstreaza conceptele fundamentale ale programarii in retea, manipularea protocolului HTTP si interactiunile concurente client-server.
Pentru rulare si testare, folositi instructiunile din www/teste.txt
O prezentare mai ampla se afla in Webserver.pptx

# Caracteristici

    Programare Socket TCP/IP: Implementeaza conceptele de baza ale programarii in retea folosind socket-uri.
    Analizarea Cererilor HTTP: Parseaza cererile HTTP si identifica diferite metode HTTP precum GET, POST, PUT si HEAD.
    Gestionarea Concurrenta a Clientilor: Foloseste fork-ul de procese pentru a gestiona simultan multiple cereri ale clientilor.
    Rezolutia Tipului MIME: Determina si raspunde cu tipurile MIME corecte bazate pe extensiile de fisier.
    Gestionarea Erorilor: Gestioneaza robust erorile de retea si problemele de analiza a cererilor HTTP.
    Servirea Fisierelor Statice: Capabil sa serveasca fisiere statice precum HTML, CSS, JPEG si PNG.

# Structura

Proiectul este structurat astfel:

    Server.c/h: Contine codul pentru initializarea serverului si gestionarea conexiunilor cu clientii.
    ClientHandler.c/h: Gestioneaza logica de prelucrare a cererilor clientilor.
    HttpServer.c/h: Implementeaza parsarea cererilor HTTP si pregatirea raspunsurilor.
    main.c: Punctul de intrare al programului, care configureaza si porneste serverul.

![image](https://github.com/Epure-Tofanel-Carlo/C-Webserver/assets/129178776/77df2bac-70e8-4050-b049-45d2d64ed569)

![image](https://github.com/Epure-Tofanel-Carlo/C-Webserver/assets/129178776/8decf344-c8ae-4298-b67d-abda242e0996)



