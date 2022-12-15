
# Instal·lació i configuració de Moodle amb Ubuntu server
1. Primer actualitzarem els paquets
![Captura de pantalla de 2022-12-15 16-24-54](https://user-images.githubusercontent.com/114162657/207912404-c768cb79-2077-4797-acc0-2038efda5762.png)
 2. Després instal·larem apache2
![Captura de pantalla de 2022-12-15 16-25-33](https://user-images.githubusercontent.com/114162657/207912758-a9b967a2-c821-4366-86e3-f907f1067d8b.png)
 3. Ara instal·larem mariadb
![Captura de pantalla de 2022-12-15 16-26-21](https://user-images.githubusercontent.com/114162657/207912938-395c2b3e-6cfa-4d85-8f0a-72a01aef0001.png)
 4.Després configurarem mysql
![Captura de pantalla de 2022-12-15 16-26-59](https://user-images.githubusercontent.com/114162657/207913296-5a24ad01-036a-4ccd-95eb-e53d0c63166f.png)
 5. Aquesta serà la configuració dels paràmetres
![Captura de pantalla de 2022-12-15 16-28-01](https://user-images.githubusercontent.com/114162657/207913446-c2cff94f-2f9b-492a-83cb-60795e8e8e4f.png)
![Captura de pantalla de 2022-12-15 16-28-12](https://user-images.githubusercontent.com/114162657/207913463-38081421-7fb6-470a-990b-6db352f4d1a1.png)
 6. Ara afegirem el repositori per descargar PHP
![Captura de pantalla de 2022-12-15 16-29-13](https://user-images.githubusercontent.com/114162657/207913803-53fc9d53-7dee-44ff-98f3-4ccd4bbc3430.png)
 7. Actualitzarem paquets
![Captura de pantalla de 2022-12-15 16-29-35](https://user-images.githubusercontent.com/114162657/207913919-96e940ee-5761-4709-a920-dbe9d060e03f.png)
 8. Ara instal·larem php7.3
![Captura de pantalla de 2022-12-15 16-30-14](https://user-images.githubusercontent.com/114162657/207914196-523f0718-c30c-4b71-95b1-6c513bda2d9c.png)
 9. Desprès baixarem el fitxer zip de moodle
![Captura de pantalla de 2022-12-15 16-30-56](https://user-images.githubusercontent.com/114162657/207914369-66774271-8271-4484-964f-d8638e07c7c1.png)
 10. Un cop descargat instal·larem unzip i descomprimirem l'arxiu al directori d'apache2
![Captura de pantalla de 2022-12-15 16-33-31](https://user-images.githubusercontent.com/114162657/207932884-f76038c6-a6c6-47c9-86a8-c13ee5984f1e.png)
 11. Un cop descomprimit posarem permisos publics al directori de moodle.
![Captura de pantalla de 2022-12-15 16-34-00](https://user-images.githubusercontent.com/114162657/207933522-96de2f68-4165-45f5-ade3-8d105792aff1.png)
 12. Entrarem a la carpeta "home" i farem una nova carpeta per a moodle i li donarem permisos per als usuaris.
![Captura de pantalla de 2022-12-15 16-34-45](https://user-images.githubusercontent.com/114162657/207933769-66e51b0c-bb9f-47fc-aeb0-aeb1a8a2b8d0.png)
 13. Ara entrarem a MariaDB.
![Captura de pantalla de 2022-12-15 16-35-07](https://user-images.githubusercontent.com/114162657/207934015-1dda44a5-c541-4abb-9358-b0af49d21e09.png)
 14. Posarem un nou usuari amb una contrasenya.
![Captura de pantalla de 2022-12-15 16-36-21](https://user-images.githubusercontent.com/114162657/207934217-2723d9e0-2fd4-4b30-aacf-14478b2b4f3b.png)
 15. Crearem una base de dades
![Captura de pantalla de 2022-12-15 16-36-44](https://user-images.githubusercontent.com/114162657/207934366-834b12dc-439b-40a5-b442-a223f453cd36.png)
 16. Donarem permisos al usuari que hem creat.
![Captura de pantalla de 2022-12-15 16-37-39](https://user-images.githubusercontent.com/114162657/207934582-7c9cc0c2-09ff-463f-9fc0-9eb65c379d29.png)
 17. Finalment posarem la seguent comanda i sortirem.
![Captura de pantalla de 2022-12-15 16-38-46](https://user-images.githubusercontent.com/114162657/207934725-5f3cf77a-d420-4591-99fa-b1c74a94b6f0.png)
 18. Ara accedirem al servidor Moodle a través d'un altra màquina connectada amb adaptador pont.
![Captura de pantalla de 2022-12-15 16-39-41](https://user-images.githubusercontent.com/114162657/207934960-353e5af2-ea40-4208-908f-7c24ad28db0a.png)
 19. Ara instal·larem uns paquets que ens demanen
![Captura de pantalla de 2022-12-15 19-06-55](https://user-images.githubusercontent.com/114162657/207935267-4384b08d-47a9-4764-b44d-042fda4a78cd.png)
![Captura de pantalla de 2022-12-15 16-40-35](https://user-images.githubusercontent.com/114162657/207935440-3ed35add-9434-4630-9ded-ed2a3b5e0fd1.png)
 20. Desprès reiniciarem el servidor web.
![Captura de pantalla de 2022-12-15 19-09-04](https://user-images.githubusercontent.com/114162657/207935610-68c38f82-602d-4d87-853e-e1eb32fac3bd.png)
 21. Un cop haguem reiniciat vorem aquesta pantalla. Escriurem aquest directori al tercer camp:
![Captura de pantalla de 2022-12-15 16-43-31](https://user-images.githubusercontent.com/114162657/207936834-9e6dc874-c67a-422e-b22a-868fd1c5fc2b.png)
![Captura de pantalla de 2022-12-15 19-16-49](https://user-images.githubusercontent.com/114162657/207936992-6d52b59a-e5eb-4f1a-80cd-73b3cee049f0.png)
 22. Al seguent pas haurem de seleccionar la base de dades MariaDB.
![Captura de pantalla de 2022-12-15 16-44-02](https://user-images.githubusercontent.com/114162657/207937463-e303ca39-e9ff-45ab-8421-d14faba2d76e.png)
 23. Ara emplenarem els camps amb les dades que vam omplir cuan vam configurar la base de dades.
![Captura de pantalla de 2022-12-15 19-22-01](https://user-images.githubusercontent.com/114162657/207937862-31b03fa5-20cf-4b7a-ab50-4dfb2c612588.png)
 24. Instal·larem els seguents paquets
![Captura de pantalla de 2022-12-15 16-46-01](https://user-images.githubusercontent.com/114162657/207938017-ab12e128-9ec8-4dcb-bfb8-9d19d81ff00e.png)
 25. Desprès cuan tinguesim la pàgina reiniciada, veurem aquesta pantalla. Li donarem a continuar per aceptar els termes i condicions.
![Captura de pantalla de 2022-12-15 16-50-44](https://user-images.githubusercontent.com/114162657/207938233-7efd2d79-2b35-40a0-8690-bc131118ba9b.png)
 26. Ara ens apareixerà un altra finestra amb tots els arxius.
![Captura de pantalla de 2022-12-15 16-52-17](https://user-images.githubusercontent.com/114162657/207938440-945e6dce-f5a6-4877-a88f-afd485126982.png)
 27. Un cop fem clic a continuar s'instal·larà moodle. Un cop finalitze clicarem continuar.
 28. Desprès ens sortirà un apartat on posarem les nostres dades personals.
![Captura de pantalla de 2022-12-15 16-54-49](https://user-images.githubusercontent.com/114162657/207939247-f599182b-ffe9-42ff-af21-267a9df92c34.png)
 29. Ara posarem les dades del nostre moodle
![Captura de pantalla de 2022-12-15 16-59-22](https://user-images.githubusercontent.com/114162657/207939397-463b2768-2a7c-42b8-a3b3-6ac25a7460fc.png)
 30. Un cop finalitzem els pasos anteriors ja tindrem moodle configurat
![Captura de pantalla de 2022-12-15 17-00-10](https://user-images.githubusercontent.com/114162657/207939568-936df852-082a-4382-a24b-98030689f3f9.png)

















