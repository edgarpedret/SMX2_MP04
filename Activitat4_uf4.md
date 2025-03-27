### Activitat 4

#### Tasca 1

- Crea una carpeta a la MV Linux a /srv/samba/compartida1 amb els permisos necessaris perquè pugui accedir tothom.

  ![image](https://github.com/user-attachments/assets/80b5ac5f-1c84-453c-a293-dee61cccf262)

  
- Crea la configuració de SAMBA per compartir la carpeta per a convidats (sense autenticació) amb lectura i escriptura.

  ![image](https://github.com/user-attachments/assets/36a7e4d7-6b15-4d0b-bdc6-543e7ef72ba4)

  ![image](https://github.com/user-attachments/assets/3e6c1173-f165-40d8-9405-69de976d2083)

  
- Reinicia el servei SAMBA.

  ![image](https://github.com/user-attachments/assets/2cd1650b-7fa5-4192-b699-e4d4e1c4bcfb)


- Comprova que tens accés des de Windows.

  
  
- Crea algun fitxer a la carpeta.
  
- Comprova que s'ha creat a Linux.
  

#### Tasca 2

- Crea una carpeta a la MV Linux a /srv/samba/compartida2 amb els permisos necessaris.
  
- Crea un usuari local anomenat user1_X (on X és el teu cognom).
  
- Afegeux l'usuari anterior a SAMBA.
  
- Crea la configuració de SAMBA per compartir la carpeta per a l'usuari anterior amb lectura i escriptura amb màscara de fitxers 755.
  
- Reinicia el servei SAMBA.
  
- Comprova que tens accés des de Windows amb les credencials de l'usuari.
  
- Crea algun fitxer a la carpeta.
  
- Comprova que s'ha creat a Linux i té els permisos 755.
  
