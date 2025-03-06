# Activitat 1 - chmod
1. Ves al teu directori personal i crea una carpeta anomenada "Exercici-X" on
X és el teu cognom.
![image](https://github.com/user-attachments/assets/ac7be5a5-a35f-4870-8803-62a08567bc15)


3. Canvia els permisos del directori perquè només el propietari tingui tots els
permisos.
![image](https://github.com/user-attachments/assets/7772d8e2-eaa7-4414-973f-9f2bc62598bb)


5. Crea un arxiu anomenat "arxiu1.txt" dins del directori anterior i verifica els
permisos.
![image](https://github.com/user-attachments/assets/17898b6a-370b-4371-8143-1f88485ae4f2)


7. Crea un grup anomenat "proves".
 ![image](https://github.com/user-attachments/assets/a8667643-4eef-4a9e-8e54-7ec7b6a3ab80)

   
9. Dona-li permisos de lectura i escriptura sobre "arxiu1.txt" al grup.
![image](https://github.com/user-attachments/assets/a74d1a58-7140-4a6f-891e-ea33b5b21807)

    
11. Crea un subdirectori anomenat "sub-X" on X és el teu cognom.
![image](https://github.com/user-attachments/assets/ede5a9bd-1784-4bca-81ae-95d41a1e39d9)

    
13. Deixa el subdirectori anterior amb permisos només per al propietari (rwx).
![image](https://github.com/user-attachments/assets/b9e7575e-b363-4fbc-b8c1-d17c40b7a08d)

    
15. Concedeix permisos d'execució al grup "proves" sobre "sub-X".
![image](https://github.com/user-attachments/assets/997e956c-e9a1-4a55-b8eb-81e8985a9a5f)

    
17. Crea un usuari anomenat "convidat".
![image](https://github.com/user-attachments/assets/49e56686-28d1-4795-b660-5cd2d24ca9ff)

    
10.Canvia els permisos del directori "Exercici-X" perquè l'usuari "convidat"
pugui accedir.
![image](https://github.com/user-attachments/assets/56c0f6aa-f457-40c2-8ef5-02af28885c28)



11.Canvia els permisos de l'arxiu "arxiu1.txt" perquè tots els usuaris tinguin
només permís de lectura.
![image](https://github.com/user-attachments/assets/018bd62a-96a5-493f-91d6-3631867dd8da)



12.Comprova que l'usuari "convidat" no pot accedir al subdirectori "sub-X".
![image](https://github.com/user-attachments/assets/a7f032bd-9e48-40cb-98eb-9536b676b568)



19. Afegeix convidat al grup "proves" i comprova que sí té accés a "sub-X".
(POTSER NECESSITES REINICIAR EL SISTEMA).
![image](https://github.com/user-attachments/assets/f05e07e9-a89f-4747-a1e7-0e3e255e65ef)

# Activitat 2 – umask

1. Crea un usuari anomenat "proves2" i mostra la seva màscara per defecte.
   ![image](https://github.com/user-attachments/assets/25a3b7e0-4548-4938-ac68-815e7c566632)

3. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-r--r-- i   els
  directoris amb rwxr-xr-x.
  ![image](https://github.com/user-attachments/assets/34234d42-870a-4a89-8bdc-11644b43da7f)

  ![image](https://github.com/user-attachments/assets/84ac26ac-8b94-4f51-905e-9f9b955ca59b)

5. Comprova que la màscara anterior funciona.
   
7. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-rw-rw- i
els directoris amb rwxrwxrwx.

9. Comprova que la màscara anterior funciona.
    
11. Modifica la màscara de proves2 perquè els fitxers els crei amb r--r--r-- i els
directoris amb r-xr-xr-x.
![image](https://github.com/user-attachments/assets/9f5a5ec3-3e71-4685-a03d-aea57aaf4ec0)

13. Comprova que la màscara anterior funciona.
    
15. Modifica la màscara de proves2 perquè els fitxers els crei amb rw--w--w- i
els directoris amb rwx--x--x.

17. Comprova que la màscara anterior funciona.
    
10.Modifica la màscara per crear un fitxer anomenat "511.txt" amb permisos r-

11.Utilitza chmod perquè els permisos de "511.txt" siguin r-x--x--x.
12.Utilitza chmod perquè el fitxer anterior tingui permisos rwxrwxr-x.
13.Utilitza chown perquè el fitxer anterior sigui propietat de l'usuari root i del
grup proves.

14. Intenta eliminar el fitxer amb l'usuari proves2. (sense sudo)

15. Afegeix l'usuari proves2 al grup proves i elimina el fitxer anterior.

