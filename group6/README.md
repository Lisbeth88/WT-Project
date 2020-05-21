# GROUP 6

OFFLINE WEB APP

[Project Brief]

[Link to the presentation]

## Members

- CRUZ OMAR
- LINDAO MARIELLA
- PITA FANNY
- TORRES DANNY


## Problem statement

OFF LINE actulizar


## Proposal

## Resumen

Nuestra propuesta va enfocado al voto electr�nico de una consulta popular realizado por estudiantes de una universidad de la Ciudad de Guayaquil, por lo que se desea implementar una soluci�n tecnol�gica, segura, accesible y confiable.

La p�gina del voto electr�nico se mostrar� como pantalla principal, el ingreso del n�mero de c�dula, contrase�a (en la contrase�a se va a utilizar un cifrado) y n�mero de PIN (�ste c�digo llegar� al estudiante como parte de la activaci�n de su participaci�n para el voto). 

Una vez que ingrese se mostrar� los datos completos del estudiante tales como nombres, apellidos, edad, direcci�n, seguido se mostrar� la pregunta de la consulta popular la misma que tendr� tres opciones, SI, NO y  NULO, una vez que el estudiante de clic en votar, existir� un proceso el cual verificar� si existe una conexi�n a la red de datos de internet y se registrar� en la base de datos.

En el caso de que no exista una conexi�n de red, es decir est� offline esta informaci�n se almacenar� en una base interna y una vez que se reestablezca la conexi�n mediante un proceso subir� a la base de datos principal.

Finalmente el Administrador tendr� la opci�n de Reporte donde podr� obtener los resultados de la consulta popular.

Tambi�n se contar� como pol�tica de Respaldo de la base de datos, que el d�a de la consulta popular, almacenar dicho respaldo con frecuencia cada media hora en otro servidor distinto que estar� ubicado en un centro de datos cercana a la universidad, para garantizar que los respaldos puedan ser usados y est�n disponibles en caso desastres.

### Ventajas

1.	Accesibilidad.- ejercer el derecho a votar desde cualquier lugar (casa, trabajo, universidad, etc.).�As� como tambi�n favorece el voto a estudiantes en pa�ses extranjeros.
2.	Eficiencia.- Existe ahorro en recursos financieros, no es necesario imprimir papeletas de la elecci�n y los certificados, es decir reduce el consumo de materias primas en papeler�a y urnas de cart�n.
3.	Fiabilidad.- Facilitan el proceso electoral, ya que ofrecen datos fiables. 
4.	Precisi�n.- publicaci�n de resultados r�pidos en cuanto a captaci�n de votos.
5.	Se implementa menor log�stica por parte de los miembros de la fuerza p�blica.�
6.	La carga de trabajo de los funcionarios electorales es liviana, reducen los errores humanos.
7.	El estudiante puede verificar su elecci�n en cualquier momento.�

### Desventajas

1.	Genera menor cantidad de empleos.�
2.	El hardware y software necesarios para su implementaci�n son elevados, considerando mantenimiento, licencias, soportes y capacitaci�n.�
3.	Se requiere estar alineados a reformas legislativas universitarias.�

## Proof of concept (DEMO)

[Screenshopt of the demos + brief description ]


## References

https://www.youtube.com/watch?v=nAIoheQ9iy8 - Let's Build an Offline Web App (AWS AppSync | GraphQL | Angular)
https://github.com/mjzone/offline
https://github.com/GoogleChromeLabs/airhorn
https://xitrus.es/blog/97/Crea_aplicaciones_web_Offline_con_Cache_de_HTML5
https://www.oas.org/es/sap/deco/seminarios/peru/pre/Hector_Hernandez.pdf
https://www.youtube.com/watch?v=H7YD6W-fGfc - C�mo funciona el Voto Electr�nico No Presencial
Aspectos tecnol�gicos del voto electr�nico
December 2007
Publisher: Oficina Nacional de Procesos Electorales (ONPE) Per�Editor: ONPEISBN: 978-9972-695-33-9
Panizo Alonso
Luis Panizo Alonso
https://www.youtube.com/watch?v=dgupZHdsBUo - El voto electr�nico por internet


******** Conexion offline *********

https://www.youtube.com/watch?v=vd_5RwnfX4M - Prueba de conexion en offline con server worker
https://www.youtube.com/watch?v=IJLlCNyZSD4                                                  
https://developers.google.com/web/fundamentals/instant-and-offline/web-storage/offline-for-pwa?hl=es  -  Almacenamiento sin conexi�n para PWA


*** YDN DB ******
http://dev.yathit.com/ydn-db/downloads.html
https://github.com/yathit/ydn-db
Clase ydn.db.Storage - http://dev.yathit.com/api/ydn/db/storage.html
https://www.youtube.com/watch?v=9wkjRGe81cA - Curso de Google Cloud Platform (GCP) - Google cloud Storage
https://www.youtube.com/watch?v=8ytpvQJNOU8 - Google Cloud Storage - Getting started with the JavaScript Sample Application
https://docs.mongodb.com/manual/changeStreams/ -n https://docs.mongodb.com/manual/changeStreams/
https://codeforgeek.com/sync-app-mysql-indexeddb/ - Synchronization between mysql and IndexedDB
 


******** IndexDB referencia************
https://www.html5rocks.com/es/features/storage
https://flaviocopes.com/indexeddb/- Dive into IndexedDB
https://developers.google.com/web/tools/chrome-devtools/storage/indexeddb - Ver y cambiar datos indexados de DB con Chrome DevTools
https://developers.google.com/web/fundamentals/instant-and-offline/web-storage?hl=es
https://rolandocaldas.com/html5/localstorage-en-html5 --- localStorage en HTML5. El fin de las cookies
https://rolandocaldas.com/html5/indexeddb-tu-base-de-datos-local-en-html5  - IndexedDB: Tu base de datos local en HTML5
https://rolandocaldas.com/html5/indexeddb-agregando-objetos-al-almacen -  IndexedDB: Agregando objetos al almac�n
https://rolandocaldas.com/html5/indexeddb-recuperando-los-datos-almacenados -  IndexedDB: Recuperando los datos almacenados 
http://www.cantabriatic.com/html5-metodos-almacenamiento-cliente/ - Html5: Metodos de almacenamiento en cliente
https://developers.google.com/web/fundamentals/instant-and-offline/web-storage?hl=es - Descripci�n general del almacenamiento web



******** Seguridad en un voto electr�nico***************

https://web.mat.upc.edu/jorge.villar/esamcid/rep/evot/reportevotingse2.html
https://rua.ua.es/dspace/bitstream/10045/94728/1/Sistema_de_votacion_electronica_basado_en_criptogr_Fajardo_Juan_Antonio_Jose.pdf
https://www.tdx.cat/bitstream/handle/10803/7043/01VMmr01de01.pdf?sequence=1&isAllowed=y  - SEGURIDAD EN LOS PROCESOS DE VOTO
ELECTR�NICO REMOTO: REGISTRO, VOTACI�N, CONSOLIDACI�N DE RESULTADOS Y AUDITORIA.

https://www.xataka.com/legislacion-y-derechos/microsoft-crea-electionguard-sistema-voto-electronico-indiferente-al-hackeo - Microsoft crea ElectionGuard

******** Cifrar y descifrar cadenas en Visual Basic **********

https://docs.microsoft.com/es-es/dotnet/visual-basic/programming-guide/language-features/strings/walkthrough-encrypting-and-decrypting-strings

******** Encriptar y guardar datos en base de datos con Visual Basic .NET ****************

https://www.youtube.com/watch?v=Z54trhnO1Wc
