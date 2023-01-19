# Instal·lació i configuració de Moodle amb Ubuntu server


1. Primer actualitzarem els paquets

![](assets/1.png)

2. Desprès instal·larem apache2

![](assets/2.png)

3. Ara instal·larem mariadb

![](assets/3.png)

4. Desprès configurarem mysql

![](assets/4.png)

## Paràmetres

Aquesta serà la configuració dels paràmetres:

![](assets/5.png)

![](assets/6.png)

5. Ara afegirem el repositori per descargar PHP

![](assets/7.png)

6. Actualitzarem els paquets

![](assets/8.png)

7. Ara instal·larem php7.3

![](assets/9.png)

8. Desprès baixarem el fitxer zip de moodle

![](assets/10.png)

9. Un cop descargat instal·larem unzip i descomprimirem l'arxiu al directori d'apache

![](assets/11.png)

10. Un cop descomprimit posarem permisos publics al directori de moodle

![](assets/12.png)

11. Entrarem a la carpeta "home" i crearem una nova carpeta per a moodle on li donarem permisos per als usuaris.

![](assets/13.png)

12.  Ara entrarem a MariaDB

13. Posarem un nou usuari amb una contrasenya

![](assets/15.png)

14. Crearem una base de dades

![](assets/16.png)

15. Li donarem permisos al usuari que hem creat.

![](assets/17.png)

16. Finalment posarem la seguent comanda i sortirem

![](assets/18.png)

17. Ara accedirem al servidor Moodle a través d'un altra màquina virtual connectada amb adaptador pont.

![](assets/19.png)

18. ara instal·larem uns paquets que ens demanen

![](assets/instalarem.png)

![](assets/20.png)

19. Desprès reiniciarem el servidor web.

![](assets/21.png)

20. Un cop haguem reiniciat veurem aquesta pantalla. Escriurem aquest directori al tercer camp.

![](assets/22.png)

![](assets/23.png)

21. Al seguent pas haurem de seleccionar la base de dades MariaDB

![](assets/24.png)

22. Ara emplenarem els camps amb les dades que vam omplir cuan vam configurar la base de dades.

![](assets/25.png)

23. Instal·larem els següents paquets

![](assets/27.png)

24. Desprès cuan tinguessim la pàgina reiniciada, veurem aquesta pantalla. Li donarem a continuar per acceptar els termes i condicions

![](assets/28.png)

25. Ara ens apareixerà un altra finestra amb tots els arxius

![](assets/30.png)

26. Un cop fem clic a continuar s'instal·larà moodle. Un cop finalitzi clicarem continuar

27. Desprès ens sortirà un apartat on posarem les nostres dades personals

![](assets/32.png)

28. ara posarem les dades del nostre moodle

![](assets/33.png)

29. Un cop finalitzem els pasos anteriors ja tindrem moodle configurat

![](assets/34.png)

